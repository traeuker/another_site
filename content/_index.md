---
title: "Understanding Search in Transformers"
draft: false
---
> "[T]here is no technique that would allow us to lay out in any satisfactory way what kinds of knowledge, reasoning, or goals a model is using when it produces some output."
> – [Sam Bowman](https://arxiv.org/abs/2304.00612) 

Most recent ML papers start with a long description of how Transformers have been incredibly successful in a huge variety of tasks. 
Capabilities are advacing rapidly, but our understanding of *how* Transformers do what they do is limited. 
Recognizing this gap, our project boldly contributes to the field of mechanistic interpretability. In particular, we focus on the [importance of search](https://www.lesswrong.com/posts/FDjTgDcGPc7B98AES/searching-for-search-4) and goal representations in transformers.

We aim to:

- Gain a mechanistic understanding of how transformers implement search, starting with [toy models](https://www.lesswrong.com/posts/svuawhk64eF8fGv6c/understanding-mesa-optimization-using-toy-models), specifically [mazes](https://arxiv.org/abs/2309.10498)
- Explore how the search process can be [retargeted](https://www.lesswrong.com/posts/w4aeAFzSAguvqA5qu/how-to-go-from-interpretability-to-alignment-just-retarget), ensuring that the AI system is aligned to human preferences
- Attempt to find scaling laws for performance, corrigibility, and interpretability on search-oriented tasks 
