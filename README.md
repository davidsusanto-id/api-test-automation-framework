```plain
api-test-automation-framework
├── src/
│   ├── main/
│   │   └── java/
│   │       └── io/
│   │           └── davidsusanto/
│   │               ├── api/
│   │               │   └── factory/
│   │               │       ├── request/
│   │               │       │   ├── common/
│   │               │       │   │   └── BaseRequestSpecFactory.java
│   │               │       │   └── auth/
│   │               │       │       └── AuthRequestSpecFactory.java
│   │               │       └── response/
│   │               │           ├── common/
│   │               │           │   ├── BaseResponseSpec.java
│   │               │           │   └── ResponseValidator.java
│   │               │           └── handler/
│   │               │               └── ResponseHandler.java
│   │               └── utils/
│   │                   └── ConfigReader.java
│   └── test/
│       ├── java/
│       │   └── io/
│       │       └── davidsusanto/
│       │           ├── context/
│       │           │   ├── TestContext.java
│       │           │   ├── ApiContext.java
│       │           │   └── DataContext.java
│       │           ├── runners/
│       │           │   ├── CucumberTest.java
│       │           │   └── CucumberDryRunTest.java
│       │           └── stepdefs/
│       │               ├── common/
│       │               │   ├── ApiSteps.java
│       │               │   ├── DataSetupSteps.java
│       │               │   ├── ResponseAssertionSteps.java
│       │               │   └── TimeAndDelaySteps.java
│       │               ├── AuthenticationSteps.java
│       │               └── UserProfileSteps.java
│       └── resources/
│           └── features/
│               └── user_profile.feature
└── build.gradle
```
