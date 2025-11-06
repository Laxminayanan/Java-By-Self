# Chapter - 5: Control Statements

## A Programming Language Uses `Control Statements` To Cause The Flow Of Execution To Advance And Branch Based On Changes To The State Of A Program. 

### Java's Program Control Statements Can Be Put Into The Following Categories: 
- Selection.
- Iteration.
- Jump.

## Selection Statements Allow Your Program To Choose Different Paths Of Execution Based Upon The Outcome Of An Expression Or The State Of A Variable. 

## Iteration Statements Enable Program Execution To Repeat One Or More Statements. (i.e., Iteration Statements Form Loops). 

## Jump Statements Allow Your Program To Execute In A Non - Linear Fashion. 


# Java's Selection Statements: 
#### Java Supports Two Selection Statements: 
- if.
- switch.
#### These Statements Allow You To Control The Flow Of Your Program's Execution `Based Upon Conditions Known Only During Runtime`. 

#### if: 
- `if` Statement In Java Is A A Conditional Branch Statement. It Can Be Used To Route Program Execution.

#### Standard Syntax: 

```java
if(BooleanExpression) Statements; 
```
- Note: `Statements` In The Standarad Syntax Can Be A Single Statement Or A Compound Statement Enclosed In Curly Braces(i.e., A Block).


### What Is The Difference Between Refering The `if-else` As: 
- if Clause And else Clause.
- if else Conditional Branching.
- if else Control Structure.
- if else blocks.
- if else statements.
- And Other Similar Terms.

### Note: Remember, Only One Statement Can Appear Directly After The `if` Or The `else`. If We Want To Include More Statements, We Need To Create The Block By Using The `{}`.

#### Explore The Statement: `White Space Is Insignificant In Java!`.

## Nested `if's`:
- A Nested `if` Is An `if Statement` That Is The Target Of Another if Or else. Nested if's Are Very Common In Programming. When You Nest `if's`, The Main Thing To Remember Is That An `else` Statement Always Refers To The Nearest `if` Statement That Is Within The Same Block As The else And That Is Not Already Associated With An else. 
###### Here Is An Example: 
<img width="672" height="212" alt="image" src="https://github.com/user-attachments/assets/4d4c447f-f712-46ce-b89b-49dbecfd7dba" />



# switch: 
#### The `switch` Statement In Java Is A Multi-Way Branch Statement. It Provides An Easy Way To Dispatch Execution To Different Parts Of Your Code Based On The Value Of An Expression. As Such, It Often Provides A Better Alternative Than A Large Series Of `if-else-if` Statements. 

###### The General Form Of `switch Statement`: 
<img width="269" height="322" alt="image" src="https://github.com/user-attachments/assets/7c44f80f-f0dd-424e-ad19-b2aa9eb13917" />

- Note:
    - 1. For Versions Of Java Prior To JDK 7, Expression Must Be Of Type byte, short, int, char, Or An Enumeration. Beginning With JDK 7, Expression Can Also Be Of Type String.
    - 2. Each Value Specified In The Case Statements Must Be A Unique Constant Expression (Such As A Literal Value). Duplicate Case Values Are Not Allowed.
    - 3.  And The Type Of Each Value Must Be Compatible With The Type Of Expression.
     
Does A Variable Is Not Allowed As The Value For The Case Statement Like: 
```java
int a = 5;
switch(expression){
    case a:
        ...
        ...
        break;
    ...
    ...
}
```



