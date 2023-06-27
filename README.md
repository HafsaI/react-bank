

# MyMoney Challenge

## Problem Statement

MyMoney platform lets investors track their consolidated portfolio value across **equity**, **debt**, and **gold**. We need to
ensure that the desired allocation percentages are equal to the actual percentages invested. The desired allocation
percentage should be derived from the initial allocation made.

**Your program should take as input:**

1. The money allocated in equity, debt and gold funds.
2. Monthly SIP payments.
3. Monthly change rate (loss or growth) for each type of fund.

**The output should be:**

1. Balanced amount of each fund for a certain month.
2. Rebalanced amount of each month if applicable.

## >[Solution] (https://github.com/geektrust/coding-problem-artefacts/tree/master)
1. OOP-Based Solution in NodeJS
2. Unit Tests in Jest
3. Build

## Assumptions

### From Problem Statement

1. The money allocated in equity, debt and gold funds.
2. Monthly SIP payments.
3. Monthly change rate (loss or growth) for each type of fund.

### Additional Assumptions Made

1. Change percentages can be declared only once for a month.
2. The system only works for a single year (Jan-Dec) as there is no way to distinguish between years from the input.

## Programming Decisions

1. Private attributes defined with a # in JS for encapsulation
2. Asset amounts are stored in arrays as opposed to storing in 3 different variables so that it's easier to scale the solution for more funds 

## Setup

To run this project, clone the project locally:

```
$ npm install
$ node geektrust.js <sample_input/<input-file>
```
To test with Jest
```
$ npm run test
```
