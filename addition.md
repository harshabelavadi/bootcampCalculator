# Addition

Scenario: Add two numbers

Given I have a calculator that's turned on.
When I enter first number
And I press "+" button
And I enter second number
And I press "=" button.
Then I see the "added sum" as the result.
