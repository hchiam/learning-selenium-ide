# Learning Selenium IDE

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Chrome extension: <https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd>

API for the chrome extension: <https://www.selenium.dev/selenium-ide/docs/en/api/commands>

- <https://github.com/hchiam/selenium-travis>
- <https://github.com/hchiam/learning-azure-devops-selenium-webdriver>
- <https://github.com/hchiam/autologinbot>
- <https://github.com/hchiam/learning-azure-devops>
- <https://github.com/hchiam?tab=repositories&q=selenium>

## Random notes

- <https://stackoverflow.com/questions/50593047/how-do-i-find-match-a-string-in-selenium-ide>
- `execute script`, `return 'value'`, `varName`
  - execute script to set var val
- `assert element present`, `xpath=//pre[contains(text(),varName)]`
  - can use var in xpath contains, but not regex
  - since can't use regex, just use assert element present and contains each non-changing part
- `echo`, `${varName}`
  - echo works like console.log
- `assert`, `varName`, `true`
  - assert to assert var val directly
- you can: `open`, `https://www/.../${varVal}/subpath/`
- `if (${labelText}.match(/someRegex/)) { return true; } else { return false };`
  ![example store text, to string, to boolean](example_storeText_string_boolean.png)
