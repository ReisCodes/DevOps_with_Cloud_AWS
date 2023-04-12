# DevOps 

### What is DevOps?

DevOps is a set of : 
- practices
- tools
- cultural philosophy

Used to integrate and automate the processes between software
development teams and IT operations teams, hence the name Dev for 
development and Ops for operations. The key emphasis of DevOps
is cross-team communication, collaboration and technology automation.

### Why DevOps?

DevOps is a tooling used across a company to bring about a multitude of benefits. 
although on the surface level it seems to have benefits in just automation the benefits to 
including a DevOps team within your company span from:

- Insight it provides to a business to improve it as a whole.
- Improves the speed and stability of all software development and deployment.
- Enables you to focus on what matters the most: The People.

All of these benefits enable a business to have culture and mindset shift to encourage collaboration
teamwork and just a more efficient work environment.

### 4 Key Pillars of DevOps 

The 4 key pillars of DevOps consist of: 

- Culture 
- Lean Product 
- Architecture 
- Technology

# AWS

### Cloud Computing

Cloud computing is a way of accessing on-demand IT resources over the internet, but 
instead of buying, owning and maintaining physical servers. Using this pay-to-go model
you can access services such as computing power, storage, and databases, as and when you 
need them from a cloud provider.

### The benefits to cloud computing 

Some main benefits to cloud computing consist of:

##### Agility

Services you require can be accessed and used almost instantly meaning you don't physically
always need the requirements for your project as you can access the via cloud providers.

##### Elasticity

Being able to scale resources up and down as you need them, keeps your projects needs flexible 
and cost-effective.

##### Cost Effective

Leading from the last point as you are on a pay as you use set up, you negate paying for resources
you might not necessarily need meaning you can keep your cost to as low as possible.

##### Deploy Globally 

With cloud services you can deploy globally within minutes reaching new geographical regions
putting applications close to almost all consumers.

### Why should we use it? and how does it fit into DevOps and better our business?

Apart from the benefits listed above, DevOps engineers benefit from cloud services as they offer an 
important boost in productivity and facilitates scalability. The cloud minimizes latency and enables centralized 
management via a unified platform for deploying, testing, integrating, and releasing applications.

A cloud platform allows DevOps teams to adapt to changing requirements and collaborate across distributed 
enterprise environments. Cloud services and tools also help address some limitations of legacy systems, 
accelerating the development process. Most cloud service providers offer CI/CD tools to automate DevOps processes.

All this encapsulates why a business would benefit from both incorporating DevOps and Cloud Services. With alot of tasks
being automated, inciting collaboration across the business and building in small increments will allow a business to 
produce higher quality applications with fewer problems in the process at the best price possible.

## Moving important credentials to .ssh file

Once we have our credential files we need to move them to our `.ssh` folder we
can do this by:
- copying the file with Press <kbd>CMD</kbd> + <kbd>SHIFT</kbd> + <kbd>C</kbd>

Navigate to our `.ssh` folder:
- Press <kbd>CMD</kbd> + <kbd>SHIFT</kbd> + <kbd>G</kbd> and then typing `~/.ssh`

And finally pasting the file with:
-Press <kbd>CMD</kbd> + <kbd>SHIFT</kbd> + <kbd>V</kbd>

##### Creating a new file to save our `.pem` file

Firstly we need to open a bash window in our terminal with the 

- `bash` command

We can then open a nano window with:

- `nano ".....".pem`

This will open an empty file where we can then paste our Information in.
On Mac save this by using 

- <kbd>CTRL</kbd> + <kbd>X</kbd> and then `Y` for yes to save the file 

Your Credentials are now saved in the `.ssh` folder.

