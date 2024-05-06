Exercise 1.1:
![img.png](img.png)

Exercise 1.2:
![img_1.png](img_1.png)
Based on the observation of the output, it can be understood that what happens is the async function will run outside of the main function that executes it. Therefore, "hey hey" might appear as the output before "howdy!" and "done!" because "hey hey" is outside the async function as the function will continue the program and execute `print!("hey hey");` while the async function is still waiting for the result from the future.