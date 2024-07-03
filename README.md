### NCStatic

Collection of Static Analysis Rules.

### Usage

For example, to run against Android Source Code:

```
$ jadx -d target_src target.apk
$ semgrep -c ./NCStatic/Rules /path/to/source/code
```

### Rules

1. Learn Semgrep: https://semgrep.dev/learn/
2. IMPORTANT: The greater the accuracy, the better the rule. Please think and test before committing.
3. Do not copy and paste other people's rules. Create your own.

### Structure

```
.
└── NCStatic/
    └── Rules/
        ├── rule-1.yaml
        └── rule-2.yaml
``` 