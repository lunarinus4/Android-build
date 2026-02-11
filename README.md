# Android-build

Diagnosing and Resolving Android Applications Building Issues: An Empirical Study

Artifact：https://drive.google.com/file/d/17UAWrJkfQaI_rkepJNHZthRMxOeYhRxN/view?usp=sharing

## License

This project is licensed under the MIT License.


# 📂 200 Applications Compilation Dataset

This repository contains a comprehensive dataset documenting the build processes, error logs, and issue resolutions for **200 open-source applications**.

The dataset covers the full spectrum of compilation outcomes—from successful "out-of-the-box" builds to complex failures requiring manual intervention. It also includes a specialized research section on using **Large Language Models (LLMs)** for automated error diagnosis and code repair.

## 🗂️ Directory Structure

The artifact is organized as follows:

```text
200 apps/
├── report.xlsx                        # Master Metadata Dataset
├── No issues apps compilation/        # Successfully compiled applications
├── Small_Issues_(apps 1-91)/          # Minor build issues (Batch 1)
├── Small_Issues_(apps 94-200)/        # Minor build issues (Batch 2)
├── Major Issues(10)/                  # Complex build failures & manual fixes
├── LLMS Research/                     # LLM-assisted debugging & resolution
└── Cant be compiled Apps (33)/        # Unresolvable applications
## 📝 Detailed Contents

### 📊 Master Data
- **`report.xlsx`**
  - The master index containing metadata for all 200 applications.
  - **Fields:** Source code links, publication years, programming languages, and build status summary.

### ✅ Successful Builds
- **`No issues apps compilation/`**
  - Documentation for applications that compiled successfully without requiring any manual intervention or dependency adjustments.

### ⚠️ Minor Build Issues
- **`Small_Issues_(apps 1-91)/`**
- **`Small_Issues_(apps 94-200)/`**
  - Documentation of minor build issues and resolutions for applications requiring small adjustments.
  - **Contents:** Step-by-step fix descriptions and screenshots.

### 🛠️ Major Issues
- **`Major Issues(10)/`**
  - Detailed records of 10 applications requiring significant manual intervention.
  - **Focus:** Resolution of complex dependencies, environment conflicts, and legacy code issues (includes screenshots).

### 🤖 LLM Research (AI-Assisted Debugging)
- **`LLMS Research/`**
  - Compilation documentation for 30 applications where Large Language Models (LLMs) were utilized to diagnose and resolve build errors.
  - **Contents:**
    - Original error logs
    - Prompts used for diagnosis
    - LLM-generated solutions
    - Verification screenshots

### ❌ Unresolvable Cases
- **`Cant be compiled Apps (33)/`**
  - Documentation of applications deemed unresolvable within the target environment.
  - **Reasons:** Missing proprietary dependencies, deprecated libraries, or insurmountable environment constraints.
