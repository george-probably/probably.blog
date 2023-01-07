---
Date: 2022-04-15 12:00
---

# Why is modern software so bad?

![Photo of a laptop screen showing lines of code](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?w=1000)<div class="caption">Photo by [Chris Ried](https://unsplash.com/@cdr6934) on [Unsplash](https://unsplash.com/)</div>

There’s no denying that Adobe Creative Cloud [really](https://twitter.com/sarandon_raboin/status/1368685514421796864), [really](https://twitter.com/DoghouseCorgian/status/1512184578173247489), [really](https://twitter.com/MyBandRomance/status/1512423823261454345) likes crashing. Some would argue that it likes crashing more than [Lance Stroll](https://www.youtube.com/watch?v=3oNCmFSsEBI)! I was recently on [The Cut Down](https://www.youtube.com/watch?v=VxI9haYnsgo) with Benjamin Aboagye, and we spent some time discussing why, and I feel like it is a significant enough topic that warrants a full write-up.

## When did this all start?

Before the widespread adoption of the internet, the world of software development was extremely different. You’d physically ship your software to customers, and that would be that. No chance for a day-one patch or to ship a sub-optimal experience with the promise of making it better down the line. What you put on the disk was all that users would get, which meant that the software had to be ready to run out of the box.

I’m sure you’ve noticed that that is no longer the case! The Samsung S22 Ultra came with an 800MB day-one update. This meant that Samsung could work on features as close to the release as possible, though that still didn’t seem to help with [Exynos devices](https://www.slashgear.com/809857/galaxy-s22-ultra-users-report-an-annoying-bug-and-theres-no-fix-in-sight/)…

Games are trending the same way too! Halo: The Master Chief Collection decided they didn’t care if the game [didn’t fit on the physical disk](https://www.eurogamer.net/halo-the-master-chief-collection-has-20gb-day-one-patch-to-unlock-multiplayer) you bought and instead offered a 20 GIGABYTE day-one patch. If you bought The Master Chief Collection in the UK on launch, brought the disk home and went to boot it up, you would have to wait for one hour for that patch to download before you could even get into the game. The worst part? Generally speaking, those that are buying disk-based games will tend to have below-average internet, meaning that they’re more likely to fall into the 17% of rural users who get less than 10mb/s. After all, if you’re getting gigabit downloads, why wouldn’t you just download it? This skyrockets that day-one patch to an eye-watering four and a half hours to download!

This has, however, allowed for some redemption stories. No Man’s Sky launched with some [truly dreadful reviews](https://arstechnica.com/gaming/2016/08/no-mans-sky-windows-port-launched-today-is-kind-of-a-mess/). It was a game that failed to deliver on many of the promises that developers Hello Games had made. The Advertising Standards Authority in the UK had to [launch an investigation](https://www.eurogamer.net/advertising-standards-launches-investigation-into-no-mans-sky) into No Man’s Sky for misleading advertising. However, they did vow to improve the game, and now, six years on, and with many free updates, it is generally a [well-received game](https://www.theguardian.com/games/2019/sep/12/no-mans-sky-beyond-a-childhood-fantasy-realised).

![Frustrated man sat staring at his laptop screen](https://images.unsplash.com/photo-1456406644174-8ddd4cd52a06?w=1000)<div class="caption">Photo by [Tim Gouw](https://unsplash.com/@punttim) on [Unsplash](https://unsplash.com)</div>

## What happens when you realise a deadline isn’t really a deadline?

Selling software on a disk means that the code needs to be ready weeks, if not months, before the release date. The software needs to be written onto millions of discs, and those discs need to be sent around the globe, ready to be bought at midnight on launch day.

What if you no longer absolutely need the code to be 100% perfect before shipping it? You let those timelines slip. “Sure, we’ll send out the disks, but we will resolve the issues in the day-one patch; we don’t even need to finalise it until the day before release.” But what happens when that day-one patch slips? Then you’re in a cycle of promising fixes in a future update.

Now you’re charging £1,499 for a display with [a built-in webcam which looks terrible](https://9to5mac.com/2022/03/17/apple-studio-display-software-update-quality/) because you decided that this webcam needs a full mobile SoC instead of just getting it right out of the box.

Obviously, the slope is neither that slippery nor that direct in most cases. Still, it is an alarming trend that is happening more and more, and it’s something that is only being worsened by the current culture around software and applications. Even if they ship the perfect app, no one is selling it as a one-off purchase anymore. Companies have realised that they can make way more money by charging you £5 per month than they can by asking for a one-off fee of £50.

The subscription model has exploded, with everything from movies (Netflix / Disney+), games (Xbox Game Pass / Playstation Plus) and music (Spotify / Tidal) all the way to food (Hello Fresh), clothing (ASOS Premier) and even coffee (Blue Coffee Box)! Fuelled almost entirely by the hope that if they charge just the right amount of money, you’ll completely forget that you actually have the choice of not paying the £15.99 per month that they are charging for a service that costs £8.99 just six years prior.

If your subscription is content, users understand that the money is for continued access to that content. If your subscription is physical goods, users understand that the money is for those goods, but what if your subscription is a piece of software? If you download it once and it doesn’t change, should it really be a subscription?

Companies like Apple and Adobe host events like WWDC and MAX (respectively) to show the world how far their latest software versions have progressed. It’s a chance for them to flex their newest features that are set to revolutionize how you use their software, whether a productivity boost or something that fundamentally changes how you work. This is exactly how they convince you to keep paying for their subscriptions. The truth is, stability updates aren’t as sexy for the end-user.

When Apple announced iOS 11, they didn’t talk about the [list of security flaws](https://support.apple.com/en-gb/HT208112) that they addressed. Instead, Senior Vice President of Software Engineering, Craig Federighi, [clucked like a chicken](https://youtu.be/VPWQrNQICU0?t=39) into an iPhone X to show off… emoji, but animals, and tracked to your face?

Even when these features are good, they face a tough lifecycle. Unless it’s a core feature of the application, their usefulness will completely live or die by the willingness of software engineers to keep it alive. This can happen either actively or passively, but how exactly?

![A laptop screen showing a user on Facebook whilst holding a phone in their right hand](https://images.unsplash.com/photo-1563986768494-4dee2763ff3f?w=1000)<div class="caption">Photo by [Austin Distel](https://unsplash.com/@austindistel) on [Unsplash](https://unsplash.com)</div>

## Passively Ruining Your Apps

This is the kind of thing that almost happens by mistake. Let’s say you’re a software developer with ten programmers. You’ve just brought in a newbie, and they want to impress, and what better way to impress than by creating a brand new feature that they know will be popular with the masses. They spend 8 hours a day working away to make this feature incredible, it launches, and everyone loves it, so what do you do? You give that programmer a promotion! They’re no longer doing the programming themselves; they’re now running a small team.

Over time, that feature gets left behind. Whether it’s because the original programmer no longer has the capacity to oversee the development, because the shoddy documentation means that no one else can figure out what is going on, or just that no one feels as passionate about the feature as the original programmer did. Now you are stuck with a feature that, at best, no longer performs as well as when you first launched it, and at worst, it is a useless piece of bloat that makes your software unstable.

This, to some extent, is why Windows is as bloated as it is. However, Windows does this by design. You can run Windows 11 on a 15-year-old Pentium 4 processor, with the ability to run software written for Windows 98! If Windows 11 took away the 25-years of legacy support, there’s no telling how many devices would randomly stop working overnight. Years after the WannaCry ransomware tore through the NHS network, they have admitted that they still have [over 2000 computers running Windows XP](https://www.computerweekly.com/news/252466838/NHS-still-has-thousands-of-PCs-running-Windows-XP)! An operating system that Microsoft stopped supporting eight years ago!

The passive destruction of your apps is something that needs constant monitoring. Sure, an OS can’t afford to break compatibility with itself from 25 years ago, but your note-taking app probably can. The balance between backwards compatibility and usefulness needs to be constantly adjusted with user feedback. If no one is using the feature that causes your application to take an extra 30-seconds to load, why is it there?

## Actively Ruining Your Apps

This one is far more sinister and casts a much darker light on the software industry. You set out to make the best to-do app the world has ever seen and to make it, you have hired 100 programmers. Thanks to the incredible app, you have convinced a million people to sign up at £5 per month, which is great, but how do you increase profit? What if you just got rid of most of the stability team. Instead of 100 programmers who balance new features with stability, cut it down to 50 programmers, and you’ve halved your development costs!

This means that there’s no immediate impact on the quality of your app, allowing you to get the benefits of an application that works great (more users who get your app more ingrained in their daily lives) without the costs. When users realise the app is barely duct-taped together, they’re too far down the rabbit hole to get out!

Not only that, but the frequently added new features make those who haven’t tried your app yet feel like the software team must be on top of everything and will try out the app just to give it a go.

In fact, no industry seems to have mastered this art quite as well as sports games have. Year after year, EA and 2K pump out games like FIFA and NBA (respectively) that are, if we’re all completely honest with ourselves, functionally the same. They are practically the same game with updated rosters. One feature that makes the game *just different enough* that they tell themselves (and customers) that they have justified the £89.99 they charge every year for the Ultimate Edition.

Imagine a world where instead of just launching a new game every year, they had a core engine that they kept for multiple years, able to update and refine to get the best possible experience. Sure, charge £90 for that core, but then have the rosters be DLC that comes at the end of every transfer window. Wouldn’t the £20 or whatever you charge for that DLC not make way more money than the effort it takes to make the game over from scratch?

Hell, even if it doesn’t make more money, I bet many fans who are only half-in on the idea of playing your annual sports game would consider that a small enough cost to buy it for the next time they have their friends over.

Nothing shows this phenomenon as much as just looking back and seeing the price of previous games in the franchises. FIFA 21, a game less than two years old, has a street value of £8, and the game has lost 93% of its value over the course of 18 months.

## How do we fix this?

Software developers need to take a step back and really commit to the time to work on stability. Sure, it’s not the most exciting thing to share with users, but it is the right option in the long term, especially when your users are professionals. As a video creator, I don’t care about the one random new feature that Premiere Pro launches with in the next update. I’m infinitely more frustrated that the lack of hardware optimization means that renders take longer than needed. A bug meant that opening a PSD within After Effects would cause it to crash immediately.

Microsoft has figured this out with Office. Sure, there’s the Office 365 (now called Microsoft 365) subscription service, where users can just throw £7.99 per month at Microsoft for Word, Excel and Powerpoint. Still, every two years, Microsoft also releases a dated version of Office. Office 2021 is a snapshot of what Microsoft 365 was at the time, but for a one-off fee. For £119.99, you know exactly what you are getting. Sure Microsoft may issue some updates with security and stability patches. Still, if you are already happy with the features, you’ll never again need to hand over a single penny to Microsoft.

This also facilitates the creation of two separate development teams within the organisation. One is inherently more focused on software stability (since Office 2021 wouldn’t accept new features anyway), and one is more focused on new software features. This ideological split between teams strikes a balance that doesn’t exist within the EA or Adobe.

EA may never take the major step to go away from the money-printing machine that is an annually released sports game, but they need to educate users that just because there isn’t anything visually new, it doesn’t mean that the game hasn’t been worked on. Adobe needs to take a step back and consider which parts of their software users actually use. They have done this recently with the removal of 3D from Photoshop, and yes, it will inevitably upset a loud minority, but you have to consider the greater good.

This all doesn’t even touch on the insane size of social media apps. Facebook has gone from the place where you catch up with friends to a one-stop-shop, allowing you to do everything from [selling your old TV](https://about.fb.com/news/2016/10/introducing-marketplace-buy-and-sell-with-your-local-community/) to finding someone to [come and watch TV with you](https://about.fb.com/news/2019/09/facebook-dating/). There are even murmurs that [Meta will be releasing their own digital currency called “Zuck Bucks”](https://www.ft.com/content/50fbe9ba-32c8-4caf-a34e-234031019371)! The Facebook app comes in at a heft 282MB, and if you want to actually message people? That’s a further 260MB for Messenger. Want to know something that took up less than that? Windows 2000, A fully functional operating system, came in at 325MB!

These apps are ballooning at an incredible pace, and they know it. Facebook Lite comes in at less than two megabytes, a 99.23% size reduction. Are you telling me that a company as large as Meta can’t find a perfectly balanced application between those two extremes?

The industry at large needs to take a step back and really figure out what exactly it is that their customers want. I don’t know what it is, but I do know that [it certainly is not this](https://i.redd.it/qlrrbn0207z51.jpg).
