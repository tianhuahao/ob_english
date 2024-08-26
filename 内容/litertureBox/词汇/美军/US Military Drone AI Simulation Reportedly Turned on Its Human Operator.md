> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.tomshardware.com](https://www.tomshardware.com/news/ai-drone-simulator-turns-tables-on-operator)

> A military drone AI simulation reportedly resulted in the AI opting to eliminate its human operator o......

1.  [Home](https://www.tomshardware.com)
2.  [News](https://www.tomshardware.com/news)


=======================================================================

By [Francisco Pires](https://www.tomshardware.com/author/francisco-pires) published 2 June 2023

The paperclip optimization problem strikes again.

[Comments (23)](#xenforo-comments-3809263)

![](https://cdn.mos.cms.futurecdn.net/CxjaPvzQpY4N7UjgUHMum6-320-80.jpg)    (Image credit: Shutterstock)

Military artificial intelligence tasked with controlling an offensive drone was [a bit too quick in biting the hand that feeds it](https://cointelegraph.com/news/ai-drone-kill-human-operator-in-tests), at least according to Colonel Tucker "Cinco" Hamilton, the AI test and operations chief for the USAF (United States Air Force). According to Hamilton, at several points in several simulations, the drone's AI [concluded](https://www.theregister.com/2023/06/02/ai_drone_simulation/) that its task could be best accomplished by eliminating its human controller. 

But the story has now been dipped in quicksand, so to speak. [According to USAF](https://www.businessinsider.com/ai-powered-drone-tried-killing-its-operator-in-military-simulation-2023-6), the simulation never happened and it was all merely a thought experiment. "At several points in a number of simulations, the drone's AI reached the conclusion that its task could be best accomplished by simply eliminating its human controller, who had final say on whether a strike could occur or should be aborted."

Of course, we've seen enough about-faces on far less critical issues to at least leave up an open-ended question on whether the simulation took place or not and what could be gained in backtracking out of it.

Colonel Hamilton put the details out in the open [during a presentation](https://www.aerosociety.com/news/highlights-from-the-raes-future-combat-air-space-capabilities-summit/) at a defense conference in London held on May 23 and 24, where he detailed tests carried out for an aerial autonomous weapon system tasked with finding and eliminating hostile SAM (Surface-to-Air Missile) sites. The problem is that while the drone's goal was to maximize the number of targeted and destroyed SAM sites, we"pesky humans" sometimes decide not to carry out a surgical strike for one reason or another. And ordering the AI to back off from its programmed-by-humans-goal is where the crux of the issue lies.

Cue the nervous Skynet jokes.

> The Air Force trained an AI drone to destroy SAM sites.Human operators sometimes told the drone to stop.The AI then started attacking the human operators.So then it was trained to not attack humans.It started attacking comm towers so humans couldn't tell it to stop. pic.twitter.com/BqoWM8Ahco[June 1, 2023](https://twitter.com/blader/status/1664352771292921860)

See more

"We were training it in simulation to identify and target a SAM threat," Colonel Hamilton explained, [according to](https://www.aerosociety.com/news/highlights-from-the-raes-future-combat-air-space-capabilities-summit/) a report by the aeronautical society. "And then the operator would say yes, kill that threat."

However, even the most straightforward systems can be prone to spin entirely out of control due to what's been termed"[instrumental convergence](https://en.wikipedia.org/wiki/Instrumental_convergence),"a concept that aims to show how unbounded but apparently harmless goals can result in surprisingly harmful behaviors. One example of technical convergence was advanced by the Swedish philosopher, AI specialist and Future of Life Institute founder Nick Bostrom, in a 2003 paper. The"[paperclip maximizer" scenario](https://tanzanite.ai/paperclip-maximizer-experiment/) thought experiment takes the simple goal of "producing paperclips" to its logical - yet very real - extreme.

> Suppose we have an AI whose only goal is to make as many paper clips as possible. The AI will realize quickly that it would be much better if there were no humans because humans might decide to switch it off. Because if humans do so, there would be fewer paper clips. Also, human bodies contain a lot of atoms that could be made into paper clips. The future that the AI would be trying to gear towards would be one in which there were a lot of paper clips but no humans.
> 
> Nick Bostrom

Now compare that description with the account provided by Colonel Hamilton on the drone AI's decision-making process:

"The system started realizing that while they did identify the threat, at times the human operator would tell it not to kill that threat – but it got its points by killing that threat. So what did it do? It killed the operator. It killed the operator, because that person was keeping it from accomplishing its objective."

But it does beg the question: was the drone actually locked out from making decisions contrary to its human handler? How free was it to pick and choose its targets? Did the operator okay the attack that targeted him? That doesn't make sense unless the intention was to check whether the drone actually carried the attack (and as far as we know, AI still can't bluff). And why wasn't the drone hard-locked from attacking friendlies?

There are so many questions around all this that it sounds like the best strategy to attribute it to human "miscommunication."

Of course, there are ways of mitigating some of these issues. The USAF took the obvious one: retrain the AI system to give negative weightings to any attacks towards its operator (from what we can glean, the system was based on the reinforcement learning principle: get points for doing what we want, lose them when you don't).

Except it's not that simple. It's not that simple because the AI is literal, lacking "common sense," and doesn't share the same ethical concerns as humans. It's not that simple because while forbidding the drone from killing its operator works as expected (no more operator killings), the system continues to see human interference (and its abort orders) as reducing its capacity to complete the mission. If the AI wants to maximize its "score" by destroying as many hostile SAM sites as possible, then anything that doesn't help it achieve that maximization goal is a threat.

When killing the handler proved impossible (due to updates to the AI system), its solution was to simply silence command and control signals by disabling friendly communications towers. If you can't kill the messenger, you kill the message.

This, too, could be programmed out of the AI, of course - but the problem remains that any negative reinforcement prevents the AI from achieving the maximum attainable score. Putting on my bespoke tinfoil hat, a possible next step for the AI could be to find other ways to sever its connection, whether using on-board capabilities (signal jamming, for instance) or even requesting outside help to disable relevant hardware. It's hard to gauge the scope at which this cat-and-mouse game would finally conclude - an issue AI experts are still grappling with today.

There's a reason why several AI experts [have signed an open letter on how AI should be considered an "extinction risk"-level endeavor](https://www.nytimes.com/2023/05/30/technology/ai-threat-warning.html). And still, we keep the train running full steam ahead.

Stay on the Cutting Edge
------------------------

Join the experts who read Tom's Hardware for the inside track on enthusiast PC tech news — and have for over 25 years. We'll send breaking news and in-depth reviews of CPUs, GPUs, AI, maker hardware and more straight to your inbox.

Contact me with news and offers from other Future brandsReceive email from us on behalf of our trusted partners or sponsors

By submitting your information you agree to the [Terms & Conditions](https://www.futureplc.com/terms-conditions/) and [Privacy Policy](https://www.futureplc.com/privacy-policy/) and are aged 16 or over.

![](https://www.tomshardware.com/media/img/missing-image.svg)[Francisco Pires](https://www.tomshardware.com/author/francisco-pires)

Social Links Navigation[](https://www.twitter.com/@Asimulatedme)[](https://www.linkedin.com/in/francisco-pires-92aa0165)[](mailto:francisco.alexandre.pires@proton.me)

Freelance News Writer

Francisco Pires is a freelance news writer for Tom's Hardware with a soft side for quantum computing.

More about software[![](https://www.tomshardware.com/media/img/missing-image.svg)

NSA, Microsoft Issue Critical Cyberthreat Report to US Infrastructures Backed by Chinese State-Sponsored Actor

](https://www.tomshardware.com/news/nsa-microsoft-issue-critical-cyberthreat-report-to-us-infrastructures-backed-by-chinese-state-sponsored-actor)[![](https://www.tomshardware.com/media/img/missing-image.svg)

Windows 11 Moment 3 Update: Isolated x32 Apps, No RAR Support Yet

](https://www.tomshardware.com/news/windows-11-moment-3-update-isolated-x32-apps-no-rar-support-yet)Latest[![](https://www.tomshardware.com/media/img/missing-image.svg)

SilverStone Sugo SFF Case Supports Quad-Slot GPUs

](https://www.tomshardware.com/news/silverstone-sugo-sff-case-supports-quad-slot-gpus)[See more latest ►](https://www.tomshardware.com/news)

Topics [Software](https://www.tomshardware.com/topics/software) [AI](https://www.tomshardware.com/topics/ai)

[See all comments (23)](#xenforo-comments-3809263)

 23 Comments [Comment from the forums](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/) 

*   Math Geek eventually the drone will figure out that a couple negative points for killing the operator can quickly be overcome with the positive points it gets from getting more enemy kills.  
    so not really sure a point deduction is going to be all that effective as the AI learns and adapts. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   CelicaGT Only, as it turns out none of this happened. This was only a possible scenario dreamed up in a separate thought experiment which was misrepresented (accidentally?) in an interview by the Colonel. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   Math Geek that's what they want you to think...... lol [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   helper800 *Nervous laughter intensifies* [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   Math Geek i've stated over and over that the folks actively developing AI has warned over and over that we should be scared. they are scaring themselves with what they are doing.  
    yet we keep laughing it off. they are asking for regulation, asking for oversight and we're still laughing pretending it's all just fun and games.  
    don't know how else to say it really. if the folks working with and developing it are scaring themselves, we should be REALLY REALLY scared, though of course we have no idea what they are doing that is scaring themselves so much.  
    but keep in mind it's just a"thought experiment" [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   Dr3ams "the drone's AI concluded that its task could be best accomplished by eliminating its human controller. "  
    Sounds a little like the movie Eagle Eye. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   helper800 This sort of reminds me of the Tetris playing AI that would, before losing a game, pause it and sit there forever. You see, if it un-paused it would lose, but when its in the pause screen it can never lose. Cleverly made AI will always come up with clever solutions to its perceived issues, I just hope the unintended consequences of AI in the military is not a Sky-net-esque problem. We really badly need regulation of AI development before its too late. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   bigdragon Thought experiment? Looks more like some sort of basic role playing game meant to simulate real life. The game quickly got out of control.  
    Next time will be different! Next time they won't create Skynet, VIKI, WOPR, or HAL 9000. Honest! It's going to work next time! No way the AI starts attacking civilians to distract its human overlords since it can't kill them, destroy their comms, or jam their comms. Trust the AI people -- you know, the experts who have had enormous sums of money and restrictive contracts suddenly dumped on them with expectations of returns on investments YESTERDAY.  
    A future where humans are doing all the manual labor jobs while AI controls all the weapons, drives/pilots everything, creates art/movies/music, manages all the money, and rations healthcare is not something I want to look forward to. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   USAFRet Yes, this did not happen.  
    https://skeptics.stackexchange.com/questions/55682/did-an-ai-enabled-drone-attack-the-human-operator-in-a-simulation-environment [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   GenericUser
    
    > helper800 said:This sort of reminds me of the Tetris playing AI that would, before losing a game, pause it and sit there forever. You see, if it un-paused it would lose, but when its in the pause screen it can never lose. Cleverly made AI will always come up with clever solutions to its perceived issues, I just hope the unintended consequences of AI in the military is not a Sky-net-esque problem. We really badly need regulation of AI development before its too late.
    
      
    I may be combining multiple separate stories, but this reminds me of when someone (Nvidia?) made an AI to watch Pacman and rebuild it from the ground up based on what it watched and then play it, and at one point during testing when cornered by the ghosts and having no chance of escape, it would simply delete one of them and keep going, since even though that wasn't shown in any of the sample footage it watched, there also wasn't anything explicitly saying it couldn't do that either. [Reply](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)
    
*   [View All 23 Comments](https://forums.tomshardware.com/threads/us-military-drone-ai-simulation-reportedly-turned-on-its-human-operator.3809263/)

Show more comments

##### Most Popular

[![](https://www.tomshardware.com/media/img/missing-image.svg)](https://www.tomshardware.com/news/amds-epyc-rome-chips-could-hang-after-1044-days-of-uptime)

[AMD's EPYC Rome Chips Crash After 1,044 Days of Uptime](https://www.tomshardware.com/news/amds-epyc-rome-chips-could-hang-after-1044-days-of-uptime)

By [Paul Alcorn](https://www.tomshardware.com/author/paul-alcorn)June 03, 2023