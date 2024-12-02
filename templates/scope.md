# Scope and Audit Details

## 1. Files In Scope
- **Requirement**: List files and directories under audit.
- **Packages**:
  - https://github.com/ldclabs/ic-panda/tree/main/src/ic_message
  - https://github.com/ldclabs/ic-panda/tree/main/src/ic_message_channel
  - https://github.com/ldclabs/ic-panda/tree/main/src/ic_message_frontend
  - https://github.com/ldclabs/ic-panda/tree/main/src/ic_message_profile
  - https://github.com/ldclabs/ic-panda/tree/main/src/ic_message_types

## 2. Lines of Code (LoC)
- **Requirement**: Total lines of code to be audited.
- **Details**:
  - **Total LoC**: 23,300
  - **Breakdown**:
    - wc -l `find src/ic_message/src -name '*.rs'`: 1848
    - wc -l `find src/ic_message_channel/src -name '*.rs'`: 1899
    - wc -l `find src/ic_message_profile/src -name '*.rs'`: 821
    - wc -l `find src/ic_message_types/src -name '*.rs'`: 500
    - wc -l `find src/ic_message_frontend/src "(" -name "*.ts" -or -name "*.svelte" ")"`: 18232

## 3. Commit Hash and Branch
- **Requirement**: Specify the branch and commit hash for the audit.
- **Details**:
  - **Tag**: `v2.7.0`
  - **Commit Hash**: https://github.com/ldclabs/ic-panda/commit/ae4d0069808220fb196c9f5f7332e09f6155e8b6

## 4. Verification Steps
- Clone and checkout:
  ```bash
  git clone git@github.com:ldclabs/ic-panda.git
  cd ic-panda
  git checkout v2.7.0
