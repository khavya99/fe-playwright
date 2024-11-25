
# playwright-practice

npx playwright codegen  - opens a new browser and code will be generated as per the things we do on UI

npx playwright test --headed ./tests/myTest.spec.ts
                    --headed  - Means we open the browser and see whats happenning while code is executed
                    - if we dont specify headed, it will by default run in headless mode
Why Playwright ? - selenium is old.Not easy to write. Slow running.
                   but have advanced version of it called selenide(its sompatible with playwright).
                 - Cypress - supports only TS/JS, no async/await, paid parallel execution, plugin culture is bad.
                   (we need to add a plugin evn to check xpath).
                 - Playwright - supports JS/TS/Java/C#/Python. 
                              - built by Microsoft
                              - supports auto waits, need not write wait until to check something
                              - fast
                              - parallel execution
                              - traceviewer, Inspectro, codegen, video
                 
Why playwright with typescript (over other programming languages)?
                              - Type script(TS) = JavaScript (JS) + More features + Static Typing