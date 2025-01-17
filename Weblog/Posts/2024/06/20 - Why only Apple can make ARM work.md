---
Date: 2024-06-20 12:01
Status: Draft
---

## I said "only Apple can make ARM work", was I right?

It has now been 3 years since apple announced to the world that they plan to move away from Intel CPUs to their own in June of 2020. The thing is, that in itself isn't major news. The huge shift comes from the change of architecture.

To greatly oversimplify, an architecture is the set of instructions that software can use to communicate with your processor. If you didn't already know, most desktop processors use an architecture known as x86, an architecture that was first introduced back in 1978! This means that although it can support almost any hardware you throw at it (and that most software is designed with it in mind), it can be pretty inefficient.

This was a large issue when mobile phones rolled around, as the inefficiency meant that it consumed more power for the same amount of output, and therefore companies like Qualcomm looked to the ARM architecture. Now, ARM isn't that much newer than x86, but they had a very different approach. ARM was designed to be as streamlined as possible, meaning it works better in power limited processes, but it also means that programs designed with x86 in mind aren't able to communicate with processors without some computationally expensive translation.

So why not use ARM for everything? The initial issue was scaling. Just because something is designed to run really well with only a little power, doesn't mean that throwing more power at it will make it run faster. And to some extent, inverse is true of x86. If you take away too much power, it loses it's efficiency.

The other issue is that most operating systems are designed with x86 in mind. Both Windows and MacOS run exclusively on x86, with Windows 10 only recently getting an ARM mode, and even that relying heavily on emulation for many apps.

The other key difference is in the processors themselves. The majority of x86 processors are designed with cores that are all the same strength. Due to manufacturing tolerances, realistically some cores with boost slightly higher than others, but as far as Intel and AMD are concerned, they are all designed to run the same. This means that if you have threaded workloads, or loads that use more than one core, you can have much better scaling. 8 cores? Your process runs 8 times faster.

The thing is, mobiles aren't used for the same kind of sustained workloads as PCs and laptops, so all mobile chip manufacturers uses what's known as a big.LITTLE architecture. This means that there are a few big cores, designed for bursty workloads like opening a webpage, but there are mostly little cores. This means that the processor can be more efficient, whilst also being sufficiently powerful.

To show that off though, let's look at a quick example: The Qualcomm Snapdragon 865 has 8 cores, with four big and four little. Out of those four big, the best one is overclocked to 2.84GHz, whereas the other three run at 2.4. The four small cores then run at 1.7GHz. Looking at a Geekbench score, we see that it has a single-core score of 891. If all cores were the same as the big one, we'd expect the multi-core score to be approximately 7000 (Assuming perfect scaling), but is actually 3253.

On the other hand, the Intel Core i7-1068NG7 has 4 cores, all running at up to a theoretical boost of 4.9GHz. The single core score is 949, whereas the multi-core score is 2298. There are a couple of factors at play here, firstly Intel CPUs will boost the speed of individual cores when there is a single-core task, so though the single core could theoretically run at 4.9GHz, when all cores were running it was at 3.8GHz. The other thing I didn't mention was power consumption. The Snapdragon 865 has a Thermal Design Power of 5 watts, whereas the i7 that was benchmarked had it's TDP set to 10 watts, and can be configured as high as 25.

Now, it is worth mentioning that this is one benchmark, and speaks nothing to the actual day-to-day experience of using either one of these chips, but it should give you a ballpark estimate of the expected performance.

Okay, so with all of the why out of the way, let's talk about how this affects Apple, and using their previous transition from PowerPC to Intel, how this could potentially go down. First of all, as the transition is announced, I expect Apple will also show off some form ARM powered hardware (or maybe even emulations software) to allow developers to start moving their software over. The first consumer hardware isn't expected to be released until 2021, but I very much expect that they will start at the low end and work their way up the stack.

I expect they'll start with all of the Macbooks, and maybe even an ARM version of the iMac, with iMac Pro and Mac Mini following through either late in 2021 or early 2022. By the end of the year, I anticipate there will be ARM versions of all of their computers, except maybe the Mac Pro.

To aid in this transition, there will most likely be some emulation software which will allow the ARM devices to run x86 software, but much like with the PowerPC transition, don't expect that to last forever.

This doesn't even mention the reverse. What if 5 years from now there's a MacOS app released that is designed for ARM but you want to run on your Intel-based Macbook? Expect it to run very inefficiently, if at all. As time goes on, only higher-and-higher end Intel devices will support MacOS before being entirely phased out. In fact, 5 years is exactly how long it took for Apple to stop supporting MacOS on PowerPC devices, so there may be a similar transitional period. 

After 7 years Apple hardware reaches "obsolete" status, so by 2028 expect that almost all Intel-powered hardware will be obsolete, and at this point, as far as Apple are concerned, the Intel powered devices no longer exist. Apple will no longer service devices, and will no longer provide parts to repair shops. 

There is a major benefit to this however, and it's that Apple will be one step closer to a universal OS for both Macs and iOS devices. Apple have been moving towards this thanks to Project Catalyst, a tool which allows iOS apps to (again, oversimplifying here), be translated so that they run on MacOS. With iPadOS gaining trackpad support, is it possible that MacOS is going to receive some kind of touchscreen support?

Now, none of this explains why only Apple can make it work. Microsoft have already tried on two separate occasions, initially with the Surface RT, and now with the Surface Pro X. Though part of the problem is definitely Microsoft, with Windows 10 just not having the same capabilities in ARM mode due to lack of app support when trying to use any professional application, or the fact that at £999, the same price as basically any other laptop using an x86 processor means that it's a lot more hassle for perceptively little benefit, means that it very much hasn't taken off. 

You see, with Windows being the default option for non-Apple computers, you have to offer something the others can't to drive sales, but Apple? Well, if you want MacOS, you need to buy a device from them, meaning if they take the plunge on ARM processors, you have no choice but to go with them. Sure, you can use your Intel powered laptop for the next few years, but sooner or later, you WILL be moving over to ARM.

For everyone's sake, I do honestly hope this works out. For better or for worse, companies tend to follow Apple's lead, and great ARM-powered laptops will hopefully lead to a world where not only is it possible to have a full Windows 10 experience on one, but that experience will have a battery life of 24 hours or more.

So I guess that's it, 2028 will mark the official end of the Intel and Apple partnership, valued in the billions of dollars over the last 15 years. With AMD snapping Intel's heels in the high end, and incredible efficiency coming from ARM processors in the low-end, it looks like Intel are the company who will suffer most from this move.