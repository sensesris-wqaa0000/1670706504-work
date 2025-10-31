# Gemini Project Context

## Build System: Maven
*   **How it works:** IntelliJ creates a standard structure (`src/main/java`, `src/test/java`) and a `pom.xml` file.
*   **Library Management:** Dependencies are declared in `pom.xml`.
*   **Advantages:**
    *   It's an industry standard.
    *   **100% Portable:** Anyone with the `pom.xml` file can build the project identically, regardless of their IDE or even from the command line.

## Key File Structure (Focus Areas)
*   **Source Code:** `src/main/java/com/example/demo`
*   **Test Code:** `src/test/java/com/example/demo`
*   **Config:** `pom.xml`

## Rules and Constraints
1.  **Dependency Rule:** You must not use any libraries that are not declared in `pom.xml`.
2.  **TDD Rule:** You must always create a Test Case in `src/test` whenever a new public method is created.
3.  **Code Style:** All code must pass Checkstyle (simulated).

## Example Commands (How to talk to me)

### To Create or Implement Code
**Provide the method signature inside `'''` markers.**
*Example:*
> สร้างเมธอดนี้ให้หน่อย:
> '''java
> public int[] sort(int[] numbers) { ... }
> '''

### To Refactor or Improve Code
**Provide the code block you want to improve.**
*Example:*
> Refactor โค้ดส่วนนี้ให้หน่อย:
> '''java
> for (int i = 0; i < numbers.length; i++) { ... }
> '''

### To Create a Test
**Provide the signature of the method you want to test.**
*Example:*
> สร้าง test สำหรับเมธอดนี้:
> '''java
> public int[] sort(int[] numbers)
> '''
