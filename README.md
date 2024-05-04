Tutorial Timer

- 1.2 Understanding how it works

    ![](assets/1.2.png)

    From observing the output, it can be understood that the async function runs independently of the main function. Consequently, "hey hey" could potentially be output before "howdy!" and "done!" because "hey hey" is outside the async function. The program proceeds to execute println!("hey hey"); while the async function is still waiting for the result of the future.