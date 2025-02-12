---
layout: default
---
# Hi, welcome and thanks for your time

## Gaza
[This investigation by Al Jazeera](https://www.aljazeera.com/program/investigations/2024/10/7/war-crimes-in-gaza-i-al-jazeera-investigations) of what is going on in Gaza is a extremely hard to watch and extraordinarily important. Please watch it only when you feel like you can handle it.

## Latest from [Blog](/blog)

{% assign sorted_items = site.posts | sort: 'date' | reverse %}
{% for post in sorted_items limit:6 %}
{% unless post.draft %}

* {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title | xml_escape }}]({{ post.url | strip }})

{% endunless  %}
{% endfor %}

## Latest from [Atualidade](/atualidade)

{% assign sorted_items = site.shorts | sort: 'date' | reverse %}
{% for post in sorted_items limit:5 %}

* {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title | xml_escape }}]({{ post.link | strip }})

{% endfor %}

## Politics and Economics

I am deeply concerned about the insane levels of _inequality_ we have today.

Today, even within wealthy countries, it is possible for someone to make 10 000 000 times more money per year than someone else working full-time.

[The disparity in wealth is all the more extreme and all the more absurd.](https://wid.world/)

While the rate of return of capital remains higher than the (real) economic growth _per capita_, the gap will only widen — unless capital is regularly re-distributed. Closing the gap must be a top priority.

__Workers must be the ones to reap the fruits of our labor.__

I would much like to see rich countries lowering the taxes for those that earn/have less than the median (or even those below the 90th percentile) while raising the overall tax revenue - so that universal education and healthcare may improve without putting the burden on those who have less.

Governments must not shy away from bold investments in education, healthcare and in the green transition.

However, they must not spend hard-earned resources in luxury projects such as professional sports and marinas or subsidizing consumerism.

I have gathered [here](https://mesquita.xyz/links) some ((exclusively) external) content on economics and politics. I'm aware french economists are very much over-represented. While i really appreciate their work, i'll try and expand this list with additional interesting material coming from other parts of the globe. Please do share with me other bodies of work you recommend!

I am a member of [Bloco de Esquerda](https://www.bloco.org/). Whatever[^1] your political inclinations, I urge you to join a political party — there's __plenty__ to do and not enough people take up their civic duty, in my opinion.

## Effective Altruism

I try to do my altruism [efficiently](https://duckduckgo.com/?q=peter+singer+effective+youtube&t=newext&atb=v330-3&iax=videos&ia=videos&iai=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DDiuv3XZQXyc). I don't see giving money away as the solution for many of today's pressing problems, but relatively rich people in rich countries can effectively help out people in poor countries. My contribution won't solve world hunger, but i'm sure each of us is capable of ending someone's hunger — actually, multiple people's — and that can only be worthwhile.

I would urge you to consider giving away the monies you can spare.

As for me, i'm a member of [giving what we can](https://www.givingwhatwecan.org/), meaning i donate 10% of the money i earn to [highly effective](https://www.thelifeyoucansave.org/giving-effectively/) charities.

I regularly support [Give Directly](https://www.givedirectly.org/):

  * (i'm an ambassador for GD. This simply means i should be able to answer questions you may have about it.)
  * ([GD's finances](https://www.givedirectly.org/financials/); [Quarterly Journal of Economics, 2016](https://haushofer.ne.su.se/publications/Haushofer_Shapiro_UCT_QJE_2016.pdf))

These are other great charities that i've supported on occasion:

* [Against Malaria Foundation](https://www.againstmalaria.com/)
* [Helen Keller International](https://www.hki.org/)
* [Evidence Action](https://www.evidenceaction.org/dewormtheworld/)
* [New Incentives](https://www.newincentives.org/)

## Internet Usage

I consider the internet to be absolutely amazing.
I try to use open source software and to be mindful of the data my online activities generate. There are HUGE tracking networks out there ([google being present in 75% of the web](https://spreadprivacy.com/biggest-tracker-networks/)) that follow you around the web, regardless of whether or not you actually use Google or Facebook. This is easy to solve! Use [DuckDuckGo's privacy essentials](https://duckduckgo.com/app) or some other extension to the same effect. Be sure to install them on you phone and PC.

WhatsApp is closed-source software with access to dozens of sensors on your phone (microphone, multiple cameras, GPS, movement sensors, et cetera) - essentially a black-box with near unlimited access, owned by Zuckerberg. I prefer not to turn my phone into such an intrusive and potentially dangerous device.
What i wrote above applies to Instagram and many other applications. To make matters worse, these track, store and monetize every interaction of the user with the app - from the time you take to scroll to (potentially) where your eyes are looking at.
Yes, these platforms do have some great content. But the content is platform-independent. All this amazing technology does not come coupled with predatory practices - some businesses just decide to make it look like an inevitability.
I use [Signal](https://signal.org/) exclusively for messaging. It is open source (anyone can inspect the code and many have - there are no hidden procedures) and, frankly, an amazing app functionally equivalent to Whatsapp.

[“Once the technology is in place, there will always be the temptation to use it. And it is poor civic hygiene to install technologies that could someday facilitate a police state.”](https://www.schneier.com/essays/archives/2013/07/mission_creep_when_e.html)

## About

I was born and raised in the Azores, and now live happily in exile in Lisbon. I work as a software engineer.

I complain a lot. That does not mean i do not appreciate how extraordinarily lucky i have been so far. I can only hope it keeps that way.

Feel free to drop me an email at f at mesquita dot xyz. Or get creative: anything at mesquita dot xyz gets through to me.


## Have a great day

\- f.

(last update: 2024.10.07)

[^1]: well... _whatever_ might be too strong of a term.
