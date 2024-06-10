### NovenStatic

Collection of Static Analysis Rules by Noventiq Pentest Team.

### Usage

For example, to run against Android Source Code:

```
$ semgrep -c ./All/Java/Android /path/to/source/code
```

### Rules

1. Learn Semgrep: https://semgrep.dev/learn/
2. IMPORTANT: The greater the accuracy, the better the rule. Please think and test before committing.
3. Do not copy and paste other people's rules. Create your own.

### Structure
REPO -> All -> LANGUAGE -> Framework(s) and General -> rule.yaml

```
.
└── NCStatic/
    └── All/
        ├── Java/
        │   ├── Android/
        │   │   ├── rule-1.yaml
        │   │   └── rule-2.yaml
        │   ├── dotCMS/
        │   │   └── rule-a.yaml
        │   ├── Liferay/
        │   │   └── rile-b.yaml
        │   └── General/
        │       ├── rule-x.yaml
        │       └── rule-y.yaml
        ├── PHP/
        │   ├── Laravel/
        │   │   └── rule-t.yaml
        │   └── General/
        │       └── rule-w.yaml
        ├── OTHER-LANGUAGE/
        │   └── General/
        │       └── rule-f.yaml
        └── README.md
``` 