## Floatless Water Valve

## Intro
Water is the world's most precious resource, and farmers know this well. As of today, livestock around the world receive drinking water from troughs an those troughs are filled with water through a valve that automatically controls water flow.  The most popular valves available today operate with a float that lifts a lever to start and stop the flow. These floats can be disrupted by freezing water or disturbance by livestock, leading to empty tanks or overflowing tanks.

A new design initiated by a team of three in Texas has been developed which eliminates the float mechanism and allows the valve to be fully submerged.  The design can save millions of gallons of water by eliminating the biggest failure mode from the popular designs: the float.  This article is authored by David Malawey to describe the features of the invention, some technical information, and the story of development.

![trough image](https://i.imgur.com/OVEhXtq.jpeg)

### Coming Up

We have plans to bring demonstration units to the beef cattle short course in College Station, TX.  The event is held annually and is the largest beef cattle education event globally.

**2024 course details:**
* August 5-7, 2024
* [Website](https://beefcattleshortcourse.com/) for beef cattle short course
* Location: 275 Joe Routt Blvd, College Station, TX 77843

## Who
Scott Jacques, equine veterinarian initiated the design from decades of experience with cattle and other livestock operations, testing of previous options, and relationships with hundreds of farmers.   He posed the problem statement and provided use-case requirements throughout the development.  David Malawey and Osnir Watanabe, both with mechanical engineering backgrounds joined the project in 2018.  David created an initial concept and prototype in 2018 and Osnir engaged his team in Brazil to generate a manufacturable prototype. Osnir's business manufactures & distributes products in the livestock reproduction industry for over two decades, employs Adriano Barrissa who led the adaptation of the concept prototype to a manufacturable assembly and a long span of testing to achieve the same performance as the initial concept.

![valve team 2018](https://i.imgur.com/HTzxAKk.jpeg)

### Valve Company
A dedicated corporation has not been established for the valve.  There are merits to forming a business for certain.  If a major investment is proposed, then a dedicated company is appropriate for the sake of accounting and transparency. As of 2024, these options are possible:
* Distribution through Osnir's Company, WTA
* Distribution through Scott's company, Applied Biotechnologies TX
* License the design to another company with a familiar consumer brand
* Form a new company for branding and distribution - or combine this with above options.

## Design Story

Concepts for floatless automatic valves have elements that date back to the 1940's in patent history but an effective product that employs this feature has been lacking in the market until now.

### A Well-known Problem

The best current solution for maintaining water troughs is to use a float valve, which generates a list of issues in practice.  In the livestock industry, the farmers solve these problems in a number of ways.

| Issue                                                       | Current Solution                                                                                                                     |
| :---------------------------------------------------------- |:------------------------------------------------------------------------------------------------------------------------------------ |
| Cattle disturb and break the float like a toy               | farmers build wooden boxes around the float valve so the animals don't disrupt it                                                    |
| The surface of the water freezes and makes float inoperable | farmers purchase heaters for troughs, to maintain the water above freezing in cold weather                                           |
| The standpipe, on top-mounted float valves, cracks          | Strong enclosures are built to prevent livestock from striking the standpipe, and insulated materials are added to prevent freezing. |
| Floats degrade under the sun by UV light                    | farmers tolerate this issue and just buy new components or new valves                                                                |
| The condition of the overall trough is unreliable           | Farmers must place troughs in visible distance in a pasture, or they make routine passes by their troughs on an ATV, regularly.      |

Each of the above problems and solutions are costly, and the efforts to deliver these solutions require their own ongoing maintenance.  If the maintenance falls short at any time, the result is wasted water. 

> [Farmer Tyler Ranch](https://youtu.be/9WZdVmc_MPU) posted a full project video just to show how to build protection around your float.  Hundreds of custom projects like this one are made just to countermeasure float issues.

<iframe src="https://www.youtube.com/embed/9WZdVmc_MPU" title="Making a Water Trough Float Guard" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

You can imagine, farmers place troughs strategically knowing the reliability of any watering station is limited, and this planning even impacts the investment to enter small-scale farming, and it is ultimately a barrier for the beef and dairy consumers to access beef from healthier, free-ranging livestock.

Consider that an acre of grass is only one step away from being a pasture:  a reliable water source.  But zero solutions come in a box - they all require expertise.  And if we reduce the expertise required by 10%, that's a possibility for millions more land owners to raise cattle.  It makes no difference to the large operations and a world of difference to the small farmers.  If we improve on the watering valve, we improve the options for sustainable agriculture.   ELIMINATE THE FLOAT!  But how?
### The Key Barrier

It is possible for a water valve to feature an internal switch that handles water depth.  When filling a container, water itself can deliver pressure to switch proportional to the weight of the water itself, which is a function of the depth.  Achieving a consistent water depth by filling and stopping is theoretically as simple as tuning a switch to match the desired depth.

However, instead of a constant pressure at a given depth, the measured pressure can change hour by hour.  This value is a combination of barometric pressure and water pressure. Since barometric pressure fluctuates daily, a simple control by means of pressure sensing would result in a tank that fills higher on a low-pressure day.  In my early evaluations, I found that a pressure swing on a stormy day can equal up to a foot of water in absolute pressure change.  That means a trough can overflow if the weather changes and the  most simple design would be inconsistent.

Surely this was not a new discovery, and earlier designers had understood it.  The question was whether any inventor made a successful countermeasure.  In 2018 I investigated current products and documents on Google Patent, and I found no designs which would achieve the desired result.  This matched our reality that floatless valves couldn't be found on the market and Scott's 30 years around livestock gave some certainty that a solution is not available on the market.   If a product existed or if a trick of the trade was available, he would have found it.

### A Novel Solution

Before we employed an IP professional to do a deep dive search, I trusted my initial search and made an effort at a proof of concept. I sketched up some methods to overcome the barrier of changing barometric pressure.  I realized that the air pressure could be delivered to the top and the bottom of the pressure actuator, so that it cancels itself out.  So simple and so precise! Still, I couldn't imagine that nobody had uncovered this solution in the past.  Could the solution be novel or could it simply be hindered by another problem we hadn't discovered?

Only a test could prove to answer this question.  I assembled a prototype which combined a common water valve which is actuated by solenoid, and an extra assembly to actuate the valve.  Instead of moving the inner plunger with an electromagnet, I coupled a magnet to my new actuator which slides up and down directly from the water pressure.  The conversion of water pressure into motion comes from a membrane, a counter-acting spring, and an enclosed space atop the valve.

After some minor adjustments, I got the valve to respond at an appropriate depth for a small tank.  It worked.  Now, we had a proof of concept. 


| first Build                                     | CAD model                                       | 3D Printed Internals                            |
|:----------------------------------------------- |:----------------------------------------------- |:----------------------------------------------- |
| ![prototype1](https://i.imgur.com/RZ8tqI2.jpeg) | ![prototype2](https://i.imgur.com/vtH1Xc0.jpeg) | ![prototype3](https://i.imgur.com/1oadRX1.jpeg) |

In November of 2018, I made an early test of the initial design concept and recorded it on video. 
![Prototype Tests ► YOUTUBE](https://youtu.be/HCn0nAhnZGY)

## Generate a Product

The next steps were to further investigate IP and to convert the first prototype into something that could serve as a legitimate product.  Materials, Methods, and the proper geometry was needed to retain the function while accommodating modern manufacturing.

This redesign work was operated by WTA, Osnir's company which also has manufacturing systems and produces its own tooling.  The work was led by Adriano, whose expertise in modeling and in functional tooling design brought about the next prototypes. 

![render of prototype 2018](https://i.imgur.com/PoJGxjl.jpeg)

In 2019 Osnir offered to initiate the Patent Search and Patent Application process through his company, [Watanabe Technologia Aplicado](https://wta.vet/)  Borrowing resources from WTA afforded a path to a globally recognized patent through the Brazilian patent office rather than the USA, which has higher fees.  After more than one year, some official documentation was returned to the team from the review process indicating that the patent application was not fully valid.  The claims (all minor features which collectively yield the novel, useful design) included two key elements that were established in much older design patents.  The two claims supporting novelty were remarked to have a prior art with an existing, matching claim.

Efforts and funding for the patent were invested by Osnir's team with intention to reimburse the costs with product sales.  In the same manner, we have an intended repayment of Dr. Jacques' decades of evaluation and characterization for value discovery, and David's engineering & prototyping efforts to establish a concept and proof thereof.  The plan for returning value to each party is essentially that the calculable costs are repaid 1:1, and the incalculable costs have been assigned by an initial agreement of future profits divided by each party at ratios defined in our early written agreements.

**Adding a team member** became of interest as the key developer in WTA, Adriano, was trusted to be an essential resource rather than an engineering expense.  So, considering the development from prototype to production, rather than calculating an hourly effort expensed to WTA, Adriano's effort is to be repaid with a ratio of future value. 

## IP Technical Path

Patent pending.

This discussion is redacted for now!

# Future Steps

The ongoing development from this float-less valve concept is of particular interest because of it's broad applications.  In truth, float valves appear in a broad host of applications, where the leading brands have innovated dozens of iterations over decades to compete with each other, and where eliminating a float would change the paradigm altogether.  For toilets and industrial tanks and so forth, the float itself is never desired, but a means to a desired result.

| Toilet Valve with Float | Pool Refill Valve with Float |
|:----------------------- |:----------------------------- |
| ![toilet diagram](https://i.imgur.com/6o04xhF.jpeg) | ![pool refill valve](https://i.imgur.com/2c3Pmbp.jpeg) |

Imagine if a new design could make every toilet tank in the world more reliable - how much water would we save?  How many instances of throwaway-and-buy-again could be eliminated?

At this time, we still have great potential to secure an improved patent, and if we capture this through fundraising or through collaboration - the opportunity can easily pay for itself by widening the markets to which we adapt this design, and increasing the value for society by improving systems beyond livestock.

### Simplicity Grows Rarer

Why is this invention important, among millions of inventions every year?

At this point in technology development, it is exceedingly rare to find an enhancement of a design that simplifies the basic concept rather than complicating it.  In every sector, "smart" devices are being released which simplify the user experience while complicating the design.  Designs like smart locks, for example add batteries and transmitters and sensors to a simple deadbolt so the user no longer needs to carry a key around.  But for every design of this sort, we add more failure modes, and less robustness.  For any given sensor, we subject a design to issues of water damage, electromagnetic interference, and power limitations.

It is easy to mistake a new design for a better design.  And with that, our whole civilization adopts more technology that relies on other systems working perfectly.   Robustness in the face of power outages, communication delays, and supply-chain interruptions is the best course for our basic needs like livestock and sanitation.

###  Images

Floatless valve installed for demonstration
![valve demo setup](https://i.imgur.com/zJxP3Bd.jpeg)

Float valves at retail stores
![retail options](https://i.imgur.com/awQKjmG.jpeg)

## Contact Us:

For business inquiries, it is best to email and copy all parties for transparency sake. 
* appliedbiosciencestx@gmail.com - for Dr. Scott Jacques, Biotechnology affiliated
* dmalawey@gmail.com - for David Malawey
* diretoria@wtavet.com.br - for Osnir's WTA and affiliates

**Businesses websites**
Business websites affiliated with Scott, Osnir, and David respectively.
* WTA ► [wtavet.com.br](https://www.wtavet.com.br/)
* Applied Biosciences Texas ► [appliedbiosciencestx.com](https://www.appliedbiosciencestx.com/about)
* SCUTTLE Robotics ► [scuttlerobot.org](https://www.scuttlerobot.org)

The workplaces for David and Scott are located in College, Station, TX - home of Texas A&M University and the Texas Aggies.  The workplace for Osnir, Adriano, and WTA is in Cravinhos, in the state of Sao Paulo, Brazil.

### Reach out for:

If you're interested in the following activities, please reach out.
* Evaluating the valve design on your farm, under a reputable company
* Investment in the project, financial or through relevant partnership
* Distribution efforts, marketing, or licensing
