# Multiplication

Scenario: (describe a scenario here)
  
  Given (state the initial condition)

  When (state the event)
  
  Then (state the effect)

Scenario: (describe a scenario here)
  
  Given (state the initial condition)
  
  When (state the event)
  
  Then (state the effect)

Scenario: Multiplication where result overflows
Given I am able to turn the calculator on
When I type in "1st number"
And I press "multiply"
And I type in "2nd number"
And I press "equals"
Then I see the "multiplied number" which can be scrolled to see the result

Scenario: Multiplication of positive and negative number
Given I am able to turn the calculator on
When I type in "positive number"
And I press "multiply"
And I type in "negative number"
And I press "equals"
Then I see the "multiplied number" as the result with negative sign

Scenario: Multiplication of number with 0
Given I am able to turn the calculator on
When I type in "1st number"
And I press "multiply"
And I type in "0"
And I press "equals"
Then I see the "0" as the result

Scenario: Multiplication of number with 1
Given I am able to turn the calculator on
When I type in "1st number"
And I press "multiply"
And I type in "1"
And I press "equals"
Then I see the "number itself" as the result

Scenario: Multiplication of 2 decimal numbers
Given I am able to turn the calculator on
When I type in "1st decimal number"
And I press "multiply"
And I type in "2nd number"
And I press "equals"
Then I see the "multiplied decimal number" as the result

Scenario: Multiplication of two irrational numbers
Given I am able to turn the calculator on
When I type in "1st irrational number"
And I press "multiply"
And I type in "2nd irrational  number"
And I press "equals"
Then I see the "multiplied irrational number" as the result

Scenario: Multiplication of two rational numbers
Given I am able to turn the calculator on
When I type in "1st rational number"
And I press "multiply"
And I type in "2nd rational number"
And I press "equals"
Then I see the "multiplied rational number" as the result

Scenario: Multiplication of two irrational numbers
Given I am able to turn the calculator on
When I type in "1st irrational number"
And I press "multiply"
And I type in "2nd irrational number"
And I press "equals"
Then I see the "multiplied irrational number" as the result

Scenario: Multiplication of a decimal number with an integer
Given I am able to turn the calculator on
When I type in "decimal number"
And I press "multiply"
And I type in "integral number"
And I press "equals"
Then I see the "multiplied decimal number" as the result

Scenario: Multiplication of numbers by pressing multiply multiple times
Given I am able to turn the calculator on
When I type in "1st number"
And I press "multiply" multiple times
And I press "equals"
Then I see the "Another operand missing" as the result

Scenario: Multiplication of numbers by pressing interleaving operators
Given I am able to turn the calculator on
When I type in "1st number"
And I press multiple operator like (*,/,-)
And I type "2nd number"
And I press "equals"
Then I see the "multiplied number" as the result

Scenario: Multiplication of numbers by pressing multiply multiple times
Given I am able to turn the calculator on
When I type in "1st number"
And I press "multiply" multiple times
And I press "equals"
Then I see the "Another operand missing" as the result
