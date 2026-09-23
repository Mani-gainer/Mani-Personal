Plan start date: 2026-09-24
Last session: none (plan not started)
Next session: Module 1 | Session A
Problems solved: total 0 (all formats 0)

## Topics

## Problems

## Weak points

## Feynman gaps

## Difficulty
Baseline

## Prerequisites
- [x] Linux toolchain reachable via WSL — Claude Code runs on Windows and compiles/runs in WSL Ubuntu (Linux 6.18.33.2-microsoft-standard-WSL2) through `wsl.exe` (accepted setup)
- [x] gcc 15.2.0 and g++ 15.2.0 present; C11 and C++17 compile and run
- [x] ASan+UBSan: out-of-bounds write caught (heap-buffer-overflow, exit 1); signed overflow caught by UBSan
- [x] TSan: pthread data race detected with -fsanitize=thread -pthread (exit 66)
- [x] valgrind 3.26.0 and gdb 17.1 installed
- [x] .claude/settings.json exists and is valid JSON
- [x] .gitignore contains bin/ and hidden_tests/
- [x] git push --dry-run works without a credential prompt (Windows git + Git Credential Manager)
