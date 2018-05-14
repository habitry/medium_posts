# How to Motivate With Leaderboards: Stop Making Losers

>Winning doesn't mean anything unless someone else loses — The Man in Black, Westworld

Leaderboards have become a common behavior change design pattern. Originally included in video games, leaderboards have started to infiltrate "gamified" products such as...

* Nike+, a fitness tracker device, which motivates users to exercise more by competing against their friends for activity points.
* Opower and MyHeat, energy track platforms, which motivate users to reduce their energy use by showing how much energy they use compared to their neighbors.
* Github, a project management tool for programmers, which motivates users to contribute to projects more by publicly displaying the number of contributions to projects by made by individual community members.

Product managers and designers use leaderboards to motivate people to use their products more. The idea is that leaderboards are motivating because people like to win and winning is motivating because it gives us status in our [communities](http://habitry.link/community).

### Competition: A Problem of Competence

But some people don't want to win. They want to avoid losing. This is a subtle yet crucial distinction. Murayama and Elliot's (2012) set of meta-analyses found the effects of competition depend on whether players desire to win or avoid losing. It depends on your goals. When you want to perform better than others, you tend to benefit from competition. But when you want to avoid performing worse than others, your performance tends to go down in competition. Similarly, Burnette et al's (2013) meta-analysis found that the desire to win is positively related to goal achievement, whereas the desire to avoid losing is negatively related to goal achievement (yay replication). Finally, Senko et al's (2017) meta-analysis found that the desire to win improves achievement only when it's accompanied by strategies that support feelings of mastery rather than helplessness.

In fact, the fear of failure tends to make us want to avoid losing rather than aim to win, and also  (Michou & Vansteenkiste, 2015)

Design patterns that foster competition, (like leaderboards) don't improve motivation and performance for all users in all situations. Competition is good for motivation and achievement only when they it helps users feel competent. Leaderboards are a motivation problem, and you can design for that.

## Designing a Motivational Leaderboard

>A finite game is played for the purpose of winning, an infinite game for the purpose of continuing the play — James P. Carse

[Self-Determination Theory](http://habitry.link/motivating-humans) argues that human beings seek and engage with activities that promise and satisfy three fundamental intrinsic motivations that all human beings across all cultures require for optimal health, well-being, and performance. All user interactions with an interface can support or frustrate the satisfaction of these Basic Psychological Needs (Peters, Calvo, & Ryan, 2018). If you want to design a motivational leaderboard, you must design with these three needs in mind.

![How Leaderboards Motivate or Demotivate](images/leaderboards/diagram1.png)

A great leaderboard supports **competence**, which is the satisfaction you get when you complete a challenging goal. You feel masterful and effective; that you're achieving things. The opposite of competence is feeling ineffective and helpless.

A great leaderboard should support **relatedness**, the satisfaction you get when you feel understood and liked by people you care about. You feel closer to the people you're playing with. The opposite of relatedness is feeling rejected and disconnected.

Finally, a great leaderboard should support **autonomy**, the satisfaction you get when you act with a sense of personal commitment and volition. The opposite of autonomy is feeling coerced and manipulated.

Well designed leaderboards promote the satisfaction of competence, relatedness, and autonomy for most users, most of the time, and they don't pit these needs against each other. For example, a risk with leaderboards is that they pit competence against relatedness. By trying to get us to win in a competition against people we play with, they can satisfy competence at the price of frustrating relatedness.

#### The Mantra: Competence and Connection over Competition

Let's breakdown leaderboards into their behavior change elements and show you how you can design these elements so that they satisfy competence, relatedness, and autonomy.

## Behavior Change Elements of a Leaderboard

A behavior change technique is an "active ingredient that brings about behavior change" (Michie et al. 2013). Most leaderboards are usually a system of four behavior change techniques:

![How Leaderboards Motivate or Demotivate](images/leaderboards/diagram2.png)

In turn, each of these behavior change techniques can support or frustrate the three [Basic Psychological Needs](http://habitry.link/motivating-humans).

![How Leaderboards Motivate or Demotivate](images/leaderboards/diagram3.png)

Let's walk through how you can design each behavior change technique to support the Basic Psychological Needs rather than frustrate them.

### 1. Goal-setting

A goal is the aim of an action (Locke & Latham, 2013). Goal-setting involves giving or guiding a user toward a goal and has become recommended as an effective building block for behavior change (Epton, Currie, Armitage, 2017)

. On a leaderboard, the metric you rank users on is the goal you want them to adopt.

* Nike+ ranks people on fitness activity points. The goal is to maximize your activity points.
* Opower, ranks people on kWh/day of energy use. The goal is to minimize energy use. MyHeat gives people a Heat Loss Rating. The goal is to reduce the score to save on your electricity bill.
* Github ranks people on number of contributions to a project. The goal is to maximize your contributions.

Not all goals are equal. Some goals support Basic Psychological Needs and some goals thwart them. Here are some suggestions to design goals that support them instead of thwarting them.

#### Provide a motivational "why"

Tell your users why you're asking them to pursue a goal (Steingut, Patall, & Trimble, 2017). Give them a reason that would make sense to them, given their goals (this supports autonomy). Typically, many products ask users to compete without giving them a simple explanation of why competing would a top slot on a leaderboard should matter to them (this frustrates their autonomy). Your users should be able to answer "I'm playing on this leaderboard because **[some reason they find valuable]**".

- Example in a leaderboard:

#### Nest extrinsic goals inside of intrinsic goals

Intrinsic goals are about pursuing ends that are inherently valuable to us, such as having fun, achieving mastery, and close relationships. Extrinsic goals are about pursuing instrumental outcomes such as wealth, fame, and hotness. In general, intrinsic goals...
  - Satisfy our Basic Psychological Needs better than extrinsic goals (Grouzet et al 2005).
  - Get us to put in more effort than extrinsic goals (Vansteenkiste, Simons, Lens, Sheldon, & Deci, 2004; Vansteenkiste, Simons, Soenens, & Lens, 2004).
  - Can feel easier to pursue than extrinsic goals (Werner, Milyavskaya, Foxen-craft, & Koestner, 2016).
  - Promote deeper learning compared to extrinsic goals (Vansteenkiste, Simons, Lens, Soenens, & Matos, 2005; Vansteenkiste, Timmermans, Lens, Soenens, & Van den Broeck, 2008)
  - Promote enhanced focus on the task at hand, compared to extrinsic goals (Vansteenkiste, Matos, Lens, & Soenens, 2007).
  - Perhaps most interestingly, pursuing extrinsic goals for intrinsic reasons, like aiming to make money to support your family, is more supportive of the Basic Psychological Needs than pursuing an extrinsic goal for extrinsic reasons (Landry et al. 2016).

On a leaderboard, make competing  about pursuing an intrinsic goal for intrinsic reasons, or at the very least, make competing an extrinsic goal done for intrinsic reasons.

- Example in a leaderboard:

#### Nest individual goals inside of team goals

Make competing more about playing with others rather than being top dog. For example, you can show your users how pursuing their individual goals helps other people on their team (Grant, 2012). This supports relatedness because it encourages users to work with each other rather than against each other.

- Example in a leaderboard:

### 2. Feedback

Feedback lets users know the progress they are making from Point A (where they are) to Point B (their goal). In general, the more often people check their progress, the more progress they make (Harkin et al. 2016). Whenever someone checks your leaderboard, they are receiving feedback.

* Nike+ ranks people on fitness activity points. The feedback is a user's position on the board.
* MyHeat, shows you areas of your home that are leaking heat and it gives you a Heat Loss Rating to tell you how great your home is at keeping heat inside.
* Github shows you the number of contributions you've made to a project and how your rate of contributions is increase or decreasing over time.

Not all goals are equal. Some goals support Basic Psychological Needs and some goals thwart them. Here are some suggestions to design goals that support them instead of thwarting them.

- Outcomes vs process vs self tracking;
- feedback (give feedback to the losers; giving autonomy support reduces pain of losses)
- how to limit ego-involvement; mastery goals protect against social comparison; winning by small amount was most enjoyable;)
- self-monoitring meta-analysis

### 3. Social Comparison

- social norms (autonomous vs controlled motives for why we're behaving)
- social comparisons are more potent when they are local, involve unknown dimensions, and manipulate the self; assimilation requires special priming
- social comparison meta-analysis

#### 4. Social Rewards

- Make them surprising
- Tie them to bigger picture life goals and aspirations
- Don't use tangible rewards
- Use intrinsic/meaningful rewards that support competence

## Conclusion

- Reminder of why the problem is important for the reader, with an example
- Reminder of their mistaken assumption
- Reminder of a solution

## Links & Notes

- https://github.com/habitry/the_motivator/blob/master/006_research_notes.md
- http://ui-patterns.com/patterns/leaderboard
- https://zurb.com/triggers/achievement/leaderboard-from-fitbit
- https://zurb.com/triggers/achievement/leaderboard-from-nike

- https://elearningindustry.com/sales-gamification-5-leaderboard-mistakes-avoid
- https://medium.muz.li/leaderboard-ui-inspiration-3a511309b07c
- http://enterprise-gamification.com/mediawiki/index.php?title=Leaderboard
- https://medium.com/search?q=gamification%20leaderboard

## References

Burnette, J. L., O'boyle, E. H., VanEpps, E. M., Pollack, J. M., & Finkel, E. J. (2013). Mind-sets matter: A meta-analytic review of implicit theories and self-regulation. *Psychological Bulletin, 139*, 655–701

Epton, T., Currie, S., & Armitage, C. J. (2017). Unique effects of setting goals on behavior change: Systematic review and meta-analysis. *Journal of Consulting and Clinical Psychology, 85*, 1182-1198.

Grant, A. M. (2012). Leading with meaning: Beneficiary contact, prosocial impact, and the performance effects of transformational leadership. *Academy of Management Journal, 55*, 458-476.

Grouzet, F. M., Sheldon, K. M., Kasser, T., Ahuvia, A., Dols, J. M. F., Kim, Y., Lau, S., Ryan, R. M., Saunders, S., & Schmuck, P. (2005). The structure of goals across 15 cultures. *Journal of Personality and Social Psychology, 89*, 800-816.

Harkin, B., Webb, T. L., Chang, B. P., Prestwich, A., Conner, M., Kellar, I., Benn, Y., & Sheeran, P. (2016). Does monitoring goal progress promote goal attainment? A meta-analysis of the experimental evidence. *Psychological Bulletin, 142*, 198-229.

Locke, E. A., & Latham, G. P. (Eds.). (2013). New developments in goal setting and task performance. Routledge.

Michie, S., Richardson, M., Johnston, M., Abraham, C., Francis, J., Hardeman, W., Eccles, M. P., Cane, J., & Wood, C. E. (2013). The behavior change technique taxonomy (v1) of 93 hierarchically clustered techniques: building an international consensus for the reporting of behavior change interventions. *Annals of Behavioral Medicine, 46*, 81-95.

Murayama, K., & Elliot, A. J. (2012). The competition–performance relation: A meta-analytic review and test of the opposing processes model of competition and performance. *Psychological Bulletin, 138*, 1035–1070.

Peters, D., Calvo, R. A., & Ryan, R. M. (2018). Designing for Motivation, Engagement and Wellbeing in Digital Experience. *Frontiers in Psychology, 9*, 797–822.

Senko, C., & Dawson, B. (2017). Performance-approach goal effects depend on how they are defined: Meta-analytic evidence from multiple educational outcomes. *Journal of Educational Psychology, 109*, 574–600.

Steingut, R. R., Patall, E. A., & Trimble, S. S. (2017). The effect of rationale provision on motivation and performance outcomes: A meta-analysis. Motivation Science, 3, 19–50.

Landry, A., Kindlein, J., Trépanier, S.-G., Forest, J., Zigarmi, D., Houson, D., & Brodbeck, F. C (2016). Why individuals want money matters: Using self-determination theory to explain the differential relations between motives for making money and employee psychological health. *Motivation and Emotion, 40*, 226-242

Werner, K. M., Milyavskaya, M., Foxen-craft, E., & Koestner, R. (2016). Some goals just feel easier: Self-concordance leads to goal progress through subjective ease, not effort. *Personality and Individual Differences, 96*, 237-242.

Vansteenkiste, M., Matos, L., Lens, W., & Soenens, B. (2007). Understanding the impact of intrinsic versus extrinsic goal framing on exercise performance: The conflicting role of task and ego involvement. *Psychology of Sport and Exercise, 8*, 771-794.

Vansteenkiste, M., Simons, J., Lens, W., Sheldon, K. M., & Deci, E. L. (2004). Motivating learning, performance, and persistence: The synergistic role of intrinsic goals and autonomy-support. Journal of Personality and Social Psychology, 87, 246-260.

Vansteenkiste, M., Simons, J., Soenens, B., & Lens, W. (2004). How to become a persevering exerciser? Providing a clear, future intrinsic goal in an autonomy-supportive way. *Journal of Sport and Exercise Psychology, 26*, 232-249.

Vansteenkiste, M., Simons, J., Lens, W., Soenens, B., & Matos, L. (2005). Examining the motivational impact of intrinsic versus extrinsic goal framing and autonomy‐supportive versus internally controlling communication style on early adolescents' academic achievement. *Child Development, 76*, 483-501.

Vansteenkiste, M., Timmermans, T., Lens, W., Soenens, B., & Van den Broeck, A. (2008). Does extrinsic goal framing enhance extrinsic goal-oriented individuals' learning and performance? An experimental test of the match perspective versus self-determination theory. *Journal of Educational Psychology, 100*, 387-399.
