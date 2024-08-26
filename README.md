# GitHub Role
This repository follows the following conventions.

## Commit Convention

| Commit Type | Description                                                                |
| ----------- | -------------------------------------------------------------------------- |
| feat        | Add new features                                                           |
| fix         | Fix bugs                                                                   |
| docs        | Modify documentation                                                       |
| style       | Code formatting, missing semicolons, no changes to the code itself         |
| refactor    | Code refactoring                                                           |
| test        | Add test code, refactor test code                                          |
| chore       | Modify package manager, and other miscellaneous changes (e.g., .gitignore) |
| design      | Change user UI design, such as CSS                                         |
| comment     | Add or modify necessary comments                                           |
| rename      | Only changes to file or folder names or locations                          |
| remove      | Only performing the action of deleting files                               |

## PR Convention

| Icon | Code                       | Description                       |
| ---- | -------------------------- | --------------------------------- |
| 🧑🏻‍🎨   | :art                       | Improve code structure/formatting |
| ⚡️  | :zap                       | Performance improvement           |
| 🔥   | :fire                      | Delete code/files                 |
| 🐛   | :bug                       | Fix bugs                          |
| 🚑   | :ambulance                 | Urgent fixes                      |
| ✨   | :sparkles                  | Introduce new features            |
| 💄   | :lipstick                  | Add/modify UI/style files         |
| ⏪   | :rewind                    | Revert changes                    |
| 🔀   | :twisted_rightwards_arrows | Merge branches                    |
| 💡   | :bulb                      | Add/modify comments               |
| 🗃    | :card_file_box             | Database-related changes          |

1. Fork 한 레포에서 작업 진행
2. 각자 feature 브랜치에서 작업 진행
3. 작업 완료 후 원본 레포의 develop 브랜치로 PR 요청
    - PR 요청 시, 위의 PR Convention을 참고하여 작성
4. 코드 리뷰 후 merge
5. 다른 사람이 merge한 코드가 있으면 pull 받아서 작업 시작 전 develop 브랜치로 merge