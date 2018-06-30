# CarND-Path-Planning
Path Planning from Self Driving Car Nanodegree of Udacity

Source code: [https://github.com/ricardoues/CarND-Path-Planning/tree/master/src](https://github.com/ricardoues/CarND-Path-Planning/tree/master/src)

## Reflection 
The code was compiled in a Dell Optiplex 3020 64 bit machine with Ubuntu 16.04.4 installed. I run the code without any application running (there is latency if there are programs running). You can see the program in action in the following videos:

[https://www.youtube.com/watch?v=CTJBitu3lW4](https://www.youtube.com/watch?v=CTJBitu3lW4)

As a starting point, I used the code provided in the Project Walkthroug. After that, I took ideas from the following blog post: 

https://towardsdatascience.com/planning-the-path-for-a-self-driving-car-on-a-highway-7134fddd8707

From the simulator we get information about the other cars, we classify the cars in three categories (mutually exclusive)  
car in my lane, car in left lane, and car in right lane. To keep the information of the classified cars, we use struct (struct is similat to classes but without methods) lines of code 13-32.


## How to compile the project
Clone the repository and inside the build directory run the following commands:

```bash
make clean
make
```


## Running the project 
Follow the instructions provided in the below link: 

[https://github.com/udacity/CarND-Path-Planning-Project](https://github.com/udacity/CarND-Path-Planning-Project)
