# Addition

Scenario: (describe a scenario here)
  
  Given (state the initial condition)

  When (state the event)
  
  Then (state the effect)

Scenario: (describe a scenario here)
  
  Given (state the initial condition)
  
  When (state the event)
  
  Then (state the effect)

Scenario: Addition of two positive numbers
Given I am able to turn the calculator on
When I type in "positive number"
And I press "plus"
And I type in "positive number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Addition of two negative numbers
Given I am able to turn the calculator on
When I type in "negative number"
And I press "plus"
And I type in "negative number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Addition of fractions
Given I am able to turn the calculator on
When I type in "1st fraction number"
And I press "plus"
And I type in "2nd fraction number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Addition of positive and negative number
Given I am able to turn the calculator on
When I type in "positive number"
And I press "plus"
And I type in "negative number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Addition of decimals
Given I am able to turn the calculator on and I am able to enter decimal numbers
When I type in "1st decimal number"
And I press "plus"
And I type in "2nd decimal number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Typing operator more than once
Given I am able to turn the calculator on
When I type in "negative number"
And I press "plus" and "another operator"
And I type in "negative number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Addition of more than 2 numbers
Given I am able to turn the calculator on
When I type in "1st number"
And I press "plus"
And I type in "2nd number"
And I press "plus"
And I type in "3rd number"
And I press "equals"
Then I see the "added number" as the result

Scenario: Adding numbers where the result goes out of range
Given I am able to turn the calculator on
When I type in "1st large number"
And I press "plus"
And I type in "2nd large  number"
And I press "equals"
Then I see the "added number" till the limit of the screen as the result

Scenario: Adding number without giving the second operand
Given I am able to turn the calculator on
When I type in "1st number"
And I press "plus"
And I type in "multiply"
Then I see the "invalid operand"  as the result
