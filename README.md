## What Belongs in JS Starter Kit
- Pkg Mgt
- Bundling
- Minification
- Sourcemaps
- Transpiling
- Dynamic HTML gen
- Centralized HTTP
- Mock API framework
- Component libs
- Development Webserver
- Linting
    - ESLint (de facto standard)
- Automated testing
    - Testing frameworks:
        - Mocha, Jasmine, AVA, Tape, Jest...
    - Assertion libraries:
        - Chai, Expect
    - Helper libraries
        - JSDOM, Cheerio (jQuery-like)
- HTTP call approaches
    Tools
        - Node
            - http
            - request (use this one if node only)
        - Browser
            - XMLHttpRequest (xhr)
            - jQuery
            - Fetch (a modern replacement for xhr) (use this)
        - Node & Browser (both client and server - isomorphic)
            - isomorphic-fetch
            - xhr
            - SuperAgent
            - Axios
    Centralize API calls for:
        preloader logic
        error handling
        single seam for mocking
    Mocking HTTP Calls
        - Nock, Hard coded JSON
        - Custom webserver: json-server, JSON Schema Faker (jsf), Express, Browsersync
    JSON server and JSON Schema faker for mock testing (faker.js, chance.js, randexp.js)
    
- Continuous Integration
    - Travis CI (for Linux), Appveyor (for Windows), Jenkins
- Automated build
- Automated deploy
- Working example app


[See build on linux-based Travis CI](https://travis-ci.org/eaparks/pluralsightBuildingAJSDevEnv)

Pluralsight: https://app.pluralsight.com/player?course=javascript-development-environment&author=cory-house&name=javascript-development-environment-m9&clip=0
