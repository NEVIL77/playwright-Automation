Playwright


Headless and with head
With out anything in th background it running call headless 
Head : you can see the whole application

Feature
- Function | API testing | Accessibility testing 
- Build in repeater | custom reporter 

cmd
- npx playwright test : it will run all the test case which is in the test folder with workers
- npx playright show-report : it will show the all the report in the local url like this http://localhost:9323 in the browser like github 
- npx playwright test tests/example.spec.ts. : it will test perticular test case only 
- npx playwright test --headed : want to see the actual testing thing in the browser 
- npx playwright test tests/example.spec.ts: 23 : want to start the debugging from the line number 23 
- npx playwright codegen : it is use to generate the test. Also known for test generator 
    - it open two window 
        1. browser window 
        2. playwright inspector 