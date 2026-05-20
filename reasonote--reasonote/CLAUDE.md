# priompt

> Working with Priompt

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/priompt/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working With Priompt

## Always Define Priompt At The Top of the `.priompt.tsx` File

`import * as Priompt from '@anysphere/priompt';`

> NOTE: If you do not do this in a `.priompt.tsx` file, you will have weird compiler errors.


## Block Components Should be Used Liberally to denote different sections of the prompt

```tsx
import {Block} from '@reasonote/lib-ai';

<Block name="Wrapper" attributes={{id: 'MyId'}}>
    <Block name="Inner">
        <Block name="EvenMoreInner">
        {`Hi`}
        </Block>
    </Block>
</Block>
```

Will compile to:

```tsx
<Wrapper id="MyId">
    <Inner>
        <EvenMoreInner>
            Hi
        </EvenMoreInner>
    </Inner>
</Wrapper>
```


## Inline Strings
- When putting strings in, indent them according to their placement in the code, and then use "trimlines" to remove starting whitespace, like:

```tsx
<Block name="Wrapper">
    {trimLines(`
        This is indented but will be trimmed
    `)}
</Block>
```


## Linebreaks

Unless you use `<br/>` between XML sections, no linebreaks will be added.

As such, you should prefer this:

```tsx
// GOOD
<Component1/>
<br/>
<Component2/>

// BAD
<Component1/>
<Component2/>
```

---
> Source: [Reasonote/reasonote](https://github.com/Reasonote/reasonote) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
