The main point in this text is that the fact that LLMs excel at generating text, can be very useful in scientific fields like math. You shouldn't listen to the common opinion of the public about what LLMs should be used for. If you ask a mathematician whether LLMs should be used when doing math, they'll probably say no because it can't solve problems for you. This way you might miss a use case that you find helpful, but others don't. Basically, a big part of math is the communication of ideas, and if you're not good at that, an LLM like chatGPT can be a useful assistant. I will present some examples of where I've found it useful.

**Proofwriting**

Writing good proofs that other people can easily read, can be hard. If you're not the perfect writer, then given an informal proof you've written, chatGPT can improve the wording in the proof and the structure. 
As an example, here's my informal proof that for any finite sets $A$ and $B$, if $|A|=|B|$, then $|A\triangle B|$ is even:
![image](https://github.com/eeropomell/AI-for-math/assets/97628152/bf999719-e1bf-4360-b283-53825aa84643)

Now, that's definitely not badly written, but some people would rather read something like:

![image](https://github.com/eeropomell/AI-for-math/assets/97628152/8f08a8e3-8aef-48f5-854e-44c18b9ccb6d)

And that's produced by GPT4 from the informal proof I wrote. What this will enable is that every person can read proofs written in the style that they prefer the most. When converting informal proofs like this, mistakes happen very rarely (esp. with GPT4), because it can just take the stuff in the original proof, and write it in the desired style.

**Research paper reading**

When reading a research paper, it'd be best if you could just focus on the concepts the paper presents, and you wouldn't have to focus at all on the sentences. 
For example in this paper https://arxiv.org/pdf/2309.17421.pdf:

>Guided by the aforementioned problems, we comprehensively organize and list our explored qualitative results. The report contains minimal quantitative benchmark results, and instead consists of mainly selected interesting qualitative examples. Despite being less rigorous, this design allows for providing a more comprehensive analysis covering a broad range of domains, tasks, working modes, and prompting techniques, under a fixed capacity. We believe this organized collection of explorations will inspire future works in emerging novel applications, next-generation multimodal task formulation, and developing advanced LMM-based intelligent systems.


Converting to an easier to read text with GPT4:

input: 
>The following is a piece of text is from an AI paper. Return a version that is easier to read (so basically just convert each sentence to simpler form of english) but has the same semantics and narrator as in the original.
>
> Guided by the aforementioned problems, we comprehensively organize and list our explored qualitative results. The report contains minimal quantitative benchmark results, and instead consists of mainly selected interesting qualitative examples. Despite being less rigorous, this design allows for providing a more comprehensive analysis covering a broad range of domains, tasks, working modes, and prompting techniques, under a fixed capacity. We believe this organized collection of explorations will inspire future works in emerging novel applications, next-generation multimodal task formulation, and developing advanced LMM-based intelligent systems.

output:
>Based on the problems mentioned before, we've arranged and listed our study results. Our report has few number-based results and mostly showcases interesting examples. Even though this approach isn't as strict, it helps us look at many different areas, tasks, ways of working, and methods within a set limit. We hope that this collection of our studies will motivate new ideas and developments in upcoming unique uses, future multi-way tasks, and smarter systems based on LMM.


If English is not your 1st language or your just trying to focus hard on the topic of the paper, then the original text can easily be an unnecessary roadblock, because of the complex words. The converted version is the exact same and it's much easier to read.

**Conclusion**

The examples here may not seem valuable to everyone, but they are to some people. The point of the examples is to show that even if chatGPT is not good at solving math problems, it can still be found a valuable tool for a mathematician. The key is to think about the things **you** personally struggle with, and try to see if an LLM can solve it. This type of thing where you can basically personalize the process of communicating scientific topics, is going to be the future. 





