# Overview
Technology in this modern era is consuming resources(smartphones, laptops,smart gadgets), at an alarming rate. As with the rising complexity of software development, new applications being developed every day along with additional features being integrated into them. It is necessary that thses 'resources' should be used in an efficient manner.

## So, what do i mean by the term 'resources'?

well, a lot applications run at a backend server which is often called the "cloud".There are several advantages in embracing the cloud, but in essence they typically fall in two categories: either operational (flexibility / speed) or economical (costs) reasons.[1](https://isiarticles.com/bundles/Article/pre/pdf/116547.pdf)

Tech giants (anazom, netflix, e-bay..) are getting creative with there software deployment techniques.
There are many ways a software can be depolyed and each way has it's own ups and downs. One popular technique is Microservices or the microservices architecture.

![Microservices](https://jpadesign.in/blog/wp-content/uploads/2019/02/MICROSERVICES.jpg)

## What are Micro-Services?

As the name suggests,It is the development of a large chunk of software (i.e. Service) into smaller pieces.
So that each service can then be tweaked, developed, and deployed on it's own.  

__In other words it's a small application that can be__

1. Scaled independently 
2. Tested independently
3. Deployed independently 
4. Has a single responsibility [2](https://www.computer.org/csdl/magazine/so/2015/01/mso2015010116/13rRUxBJhDX)

## Are mocroservices important?

Well, it depends on the complexity of an application. As the higher the complexity higher the likehood that it will
be developed using Microservices.

__Before microservices, monolithic was the was to go, However it lacked in the following ways__

1) Lack of flexibility (i.e. Build using a single technology)
2) Unreliability       (i.e. Whole system collapses due to the failure of a single unit)
3) Non-Scalability     (i.e. Applications coundn't be easily scaled since the entire system would need to be rebuilt)
4) Interdependency     (i.e. Developers lackd independence)
5) Development pace    (i.e. Development of an application takes a lot of time) 

## How is Microservices better than the monolithic architecture?

__The Microservice architecture overcomes the monolithic architecture in the following ways__

1) Multiple components
2) Logical Functionality Boundries 
3) Easy Routing
4) Decentralized
5) Fail-proof
6) Evolutionary

## Examples of microservices ##

1) __Netflix__ has a widespread architecture that has evolved from monolithic to SOA.  It receives more than one billion calls every day, from more than 800 different types of devices, to its streaming-video API.  Each API call then prompts around five additional calls to the backend service.

2) __Amazon__ has also migrated to microservices.  They get countless calls from a variety of applications—including applications that manage the web service API as well as the website itself—which would have been simply impossible for their old, two-tiered architecture to handle.

3) The auction site __eBay__ is yet another example that has gone through the same transition.  Their core application comprises several autonomous applications, with each one executing the business logic for different function areas.

## When to use Microservices ? ##

1) Where Dcentrallzation core aspect from the beginning of any project
2) The application of intrest will be subjected to high volumes of internet traffic
3) Where long-term benefits are preferred over short-term benefits
4) Haveing the right set of resources to design, develop, and deploy applications
5) Organizations and teams must be commited to using cutting edge technologies

__References:__

1) https://marutitech.com/microservices-architecture-in-2019/
2) https://smartbear.com/solutions/microservices/
