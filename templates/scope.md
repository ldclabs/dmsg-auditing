# Scope and Audit Details

## 1. Files In Scope
- **Requirement**: List files and directories under audit.
- **Files**:
  - `src/bridge/*`
  - `src/utils/linker.rs`

## 2. Lines of Code (LoC)
- **Requirement**: Total lines of code to be audited.
- **Details**:
  - **Total LoC**: 10,000
  - **Breakdown**:
    - `src/bridge/`: 5,000
    - `src/utils/`: 2,500

## 3. Commit Hash and Branch
- **Requirement**: Specify the branch and commit hash for the audit.
- **Details**:
  - **Branch**: `main`
  - **Commit Hash**: `abc123def456`

## 4. Verification Steps
- Clone and checkout:
  ```bash
  git clone https://github.com/project/repo.git
  cd repo
  git checkout abc123def456
