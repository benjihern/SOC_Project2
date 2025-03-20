Project 2 Report

Import a Pong IP within Vivado and modify it so that ball and paddle data can be read from an ABP interface. With this data, predict the landing position of the ball on the oponents side. In essence, create a CPU player that will never miss the ball with its paddle whenn playing against a human player. Make sure to not follow the ball, instead predict its landing position. 

During this lab, I faced several challenges while implementing the intelligent Pong system. The biggest issue was modifying the Pong IP to expose the ball and paddle positions through the APB interface. In the process, I accidentally deleted critical files and had to recreate the IP from scratch. Another challenge was getting the LED indicators to work, which I later traced to not creating a new Vitis project after making hardware changes. Setting up UART communication with PuTTY was fairly straightforward, though configuring the APB interface parameters required careful attention.

This assignment provided valuable experience in IP modification and APB interface implementation. I found that calculating the ball's trajectory was simpler than expected. After researching different methods online, I developed my own approach for predicting the ball’s landing position, which worked well. The project reinforced the importance of proper project management in embedded systems, particularly the need to regenerate software projects after hardware modifications. I also gained hands-on experience debugging APB interface connections and exposing internal game states through hardware interfaces.

