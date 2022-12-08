# Advent of Code

## 📆 Create codebase for new Advent of Code day
```
mason make advent_of_code_day -o ./src/challenges
```

Creates the following architecture:

```
lib/
    src/
        challenges/
            advent_of_code_{{day}}
                data/
                test/
                    advent_of_code_{{day}}_test.dart
                advent_of_code_{{day}}.dart
```