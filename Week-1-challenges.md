# WEEK CHALLENGES (WEDNESDAY)
## A. PIZZA 🍕
### 1. Know what flavor of pizza we are going to cook
### 2. Verify which ingredients are available and which ones are not
### 3. Buy the ingredients that are missing
### 4. Prepare the ingredients so they are ready from the beginning
### 5. Prepare and shape the dough
### 6. Add the sauce and ingredients to the dough
### 7. Prepare the oven to the correct temperature
### 8. Put the pizza in the oven and wait for 15 minutes
### 9. Take out the pizza and enjoy it.

## B. Hot N Cold 🥶
### 1. Know whether we want to convert from C to F or from F to C.
### 2. Obtain the value to be converted -> N
### 3. Convert from C to F
#### 3.1 Use the formula -> R = (N * 1.8) + 32
#### 3.2 Return the result in degrees Fahrenheit -> R°F
### 4. Convert from F to C
#### 4.1 Use the formula -> R = (N – 32) * .5556
#### 4.2 Return the result in degrees Celsius -> R°C
### 5. End the algorithm.

## C. Geometry 📐
### 1. Know which geometric figure we want to know its volume.
### 2. If the figure to find the volume is a pyramid:
#### 2.1 Ask for the values of its base and height, and store them in variables as bl = base length, bw = base width and h = height.
#### 2.2 Use the formula with the values of the base and the height -> R=(1/3)(bl * bw * h)
#### 2.3 Return the result of the volume of the pyramid with its respective unit.
### 3. If the figure to find the volume is a cube:
#### 3.1 Ask for the value of its area and store it in a variable as a = area.
#### 3.2 Use the formula for the volume -> R=a^3
#### 3.3 Return the result of the volume of the cube with its respective unit.
### 4. If the figure to find the volume is a sphere:
#### 4.1 Ask for the value of its radius and store it in a variable as r = radius.
#### 4.2 Use the formula for the volume -> R= ((4/3)(πr))^3
#### 4.3 Return the result of the volume of the sphere with its respective unit.
### 5. End the algorithm.


# WEEK CHALLENGES (THURSDAY)

## A. Numbers 📊
### 1. Obtain the value of the number to be evaluated and save it in a variable N.
### 2. Save the value of N modulo 2 in a variable called R -> R = N % 2
### 3. If the result R is equal to 0 -> R == 0
#### 3.1 Return the number is even.
### 4. If not, if R is not equal to 0 -> R != 0
#### 4.1 Return the number is odd.
### 5. End the algorithm.

![image](https://user-images.githubusercontent.com/115180055/229383097-eac2e192-3651-4dac-8e86-e320bc5081ad.png)

## B. Date of birth 👧
### 1. Ask for date of birth and store it in a variable called DOB
### 2. Store the current date in a variable called current_date
### 3. Create a variable called age, which will be equal to current_date minus DOB -> age = current_date - DOB
### 4. Print the value of age
### 5. End the algorithm

## C. Treasures 👑
### We have three chests, which tell us that at least one of them contains a treasure. Each chest has a message, but all the messages are lies.

### A: The middle chest has a treasure.
### B: All the chests have treasures.
### C: Only one of these chests has treasures.

### 1. Based on what the message from chest A tells us, we know that chest B does not contain a treasure, since the message says that B has a treasure, but all the messages are lies.

### 2. Based on what the message from chest B tells us, we know that not all the chests have treasures, since we already excluded chest B based on what chest A said.

### 3. Finally, what chest C tells us is that only one of these chests has a treasure, but since all the messages are lies, we know that the treasures are in the only two remaining chests, which would be chest A and chest C.

### 4. Therefore, we conclude that the treasures are located in chests A and C.
