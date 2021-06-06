# Cucumber Demo Project

VSCode Extensions
- [Cucumber Gherkin](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete)

You can choose between `scenario` and `scenario outline`. 
Use `scenario outline` for more generic test case.

`<day>` is a variable in cucumber.


## Cucumber Scenario 
```
Feature: Is it Friday yet?
    Everybody wants to know when it's Friday

    Scenario: Monday isn't Friday
        Given today is Monday
        When I ask whether it's Friday yet
        Then I should be told "Nope"


    Scenario: Friday is Friday
        Given today is Friday
        When I ask whether it's Friday yet
        Then I should be told "TGIF"
```

## Cucumber Scenario Outline
[is_it_friday.feature](./test/feautres/is_it_friday.feature)


[Source](https://www.youtube.com/watch?v=x4jP9ksCnMY)