---
template: blog-post
title: Do Not Be Boring, Have Some Fun!
slug: /animation
date: 2021-04-04 19:00
description: "Animations or transitions both are great tools. "
featuredImage: /assets/1_7rr1n9dbuy3z7cfxedw7aw.png
---
Why Should You Use CSS Animation?

Nobody likes to see a website with very basic elements, text, buttons, and icons. In order to give your website that boost it needs in viewership, you must familiarize yourself with CSS animation. Humans are extremely good at noticing movement and reacting to it. Its literally hardwired into our brains in order to understand what’s around us or what’s in front of us. The main reason you are creating a website is to show off your design and grab viewers’ attention. Animation is a keyway of doing this. Animation is a very important and powerful tool in helping us communicate our content effectively, help give attention to detail, and in all leave our visitors pleased with our design. Animation can also help decrease the cognitive load on our brains. This following code pen shows a simple animation using a hover effect on any text that you may have. This effect is simple but gives our buttons, text, or even links an elegant appeal.

<iframe height="265" style="width: 100%;" scrolling="no" title="mdRwEQx" src="https://codepen.io/shaheerashan/embed/mdRwEQx?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/shaheerashan/pen/mdRwEQx'>mdRwEQx</a> by shaheerashan
  (<a href='https://codepen.io/shaheerashan'>@shaheerashan</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

<figcaption>

Hover Me Text (inspired by <a href='https://codepen.io/bhautikbharadava/pen/OdPzdW'>@bhautikbharadava</a>

 </figcaption>

What are Keyframes?

As you might have noticed in the code pen example above, I chose to use @keyframes at-rule. Once you have defined the timing for your animation then its time to use the @keyframes at-rule. Each keyframe lets us describe what the animation element should render at the chosen time in the sequence. Fore example the animation sequence is done in percentages, meaning 0% is the first moment of the animation, while 100% is the animations final form. I have chosen to optionally include additional keyframes that describe steps in between 0-100% that will make my hover text more elegant and pleasing. This example shows how you can easily create highlighted links for your web design. I set up the keyframes with the name “anchor-underline”. When we want keyframes to have the same properties, we can list them side by side separated by commas. In my effect I chose the animation to have no change in the first 10% of the keyframe. Then it will animate from 10-40% and remain that will till 60%. Very little html is needed for this effect. Also, the CSS in this example is very little and self-explanatory. Basically, I wrote the code for the ending effect and detail of my link with (: after.) Then I went along and created the hover and the before effect. Once I had the timing on my animation set, then it was time to create the keyframes to show the animation steps and ease them in. Keyframes are great since they can show steps on what you want your design to do.



Transitions vs Animations

In this topic I will discuss the differences of transitions and animations. Transitions can be a great tool to use when we want an element to change from one state to another. In my example I used the transition state to create a hover effect along with animation to create my steps using the keyframes. Transitions help change an element from one state to another smoothly. Best time to use transitions is when you want simple changes on your web site. For example, subtle change in font color, most commonly used on hover states. They work well when someone hovers or taps a button. Animations are a more powerful and more detailed tool to use instead of transitions. Animations can have multiple steps in-between the beginning and end state. This is achieved with the above mentioned keyframes. Animations are most commonly used when you need something to move right as soon as the page loads and the animation can be on repeat without having the user to interact with it. You can also have timed animations which run for a certain amount of time. Animations are also a great tool when having an item move across your screen on a cursor hover. Some text may overlay or highlight when moving across your web design. I have an example shown below showing timed animation taken from <https://cssanimation.rocks/transition-vs-animation/>.

<iframe height="382" style="width: 100%;" scrolling="no" title="Baymax face - Hero Number 6 " src="https://codepen.io/donovanh/embed/ZYaMjw?height=382&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/donovanh/pen/ZYaMjw'>Baymax face - Hero Number 6 </a> by Donovan Hutchinson
  (<a href='https://codepen.io/donovanh'>@donovanh</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

So in conclusion, animations are a more series of complex movements created with multiple steps. Transitions on the other hand are used for creating smooth transitions from one state to another. Many people prefer transitions since they are very easy to apply and even easier to generate. Now if you want more control on animating an element you can through a series of steps, or if you want the animation to load as soon as the page opens you might want to use keyframes for a better effect.