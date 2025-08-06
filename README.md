# WBB Loader - Corruption Fix Utility

> [!WARNING]
> **This is a closed-source, pre-compiled utility.** It is provided as a courtesy to the community. If you do not trust the author or the WBB project, **do not run this tool.** It is designed to modify local application data as described below. It does not make any network requests.

This is a small, standalone utility designed to resolve a specific data corruption issue that can occur with the main WBB Loader under certain circumstances. If your loader fails to start and displays a "corrupted!" message, this tool is designed to fix it.

## Problem Description

In rare cases, system instability, unexpected shutdowns, or conflicts can cause the loader's local profile data to become corrupted. This prevents the loader from starting correctly and may result in a permanent error message.

This utility safely resets the corrupted profile data to a clean state, allowing the loader to run normally again.

## Features

*   **Simple & Safe:** A single-click solution to a complex problem.
*   **Standalone:** No installation required. Just run the executable.
*   **One-Time Use:** The utility is designed as a one-time fix. It ensures the integrity of the repair process and prevents further data issues.
*   **Lightweight:** A minimal footprint with no external dependencies.

## How to Use

**Important:** Please follow these steps exactly.

1.  **Close the WBB Loader completely.** Make sure it is not running in the background.
2.  **Close any unnecessary background applications,** especially development tools, debuggers, or system analysis software. This helps prevent the corruption from reoccurring.
3.  Download the latest version of `wbb_reset_ui.exe` from the [Releases](https://github.com/hutaoshusband/wbb_reset_ui/releases ) page.
4.  Run `wbb_reset_ui.exe`. A small window will appear:
    ![Screenshot of the Reset Tool UI](https://github.com/hutaoshusband/wbb_reset_ui/blob/main/screenshot-reset-tool.png?raw=true )
5.  Click the **"Reset"** button.
6.  You will see a confirmation message ("Profile reset successfully!").
7.  You can now start the WBB Loader again. The corruption issue should be resolved.

## Important Note

This utility is a **single-use emergency tool**. After running it successfully, it will lock itself to prevent accidental re-use. This is a safety feature. If the corruption issue happens again, it may indicate a more serious problem with your system environment. Please ensure your system is stable and free of conflicting software before running the loader.

## Disclaimer

This tool is provided "as-is" without any warranty. It is intended solely for fixing the described data corruption issue with the WBB Loader. The author is not responsible for any misuse or damage resulting from the use of this software. Use at your own risk.
