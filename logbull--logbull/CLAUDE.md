# logbull

> Write ReactComponent with the following structure:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/logbull/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Write ReactComponent with the following structure:

interface Props {
   someValue: SomeValue;
}

const someHelperFunction = () => {
    ...
}

export const ReactComponent = ({ someValue }: Props): JSX.Element => {
    // first put states
    const [someState, setSomeState] = useState<...>(...)

    // then place functions
    const loadSomeData = async () => {
        ...
    }

    // then hooks
    useEffect(() => {
       loadSomeData();
    });
   
    // then calculated values
    const calculatedValue = someValue.calculate();

    return <div> ... </div>
}

---
> Source: [logbull/logbull](https://github.com/logbull/logbull) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
