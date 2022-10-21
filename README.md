# Wikipedia GPT-3 Bot

REPL bot that answers questions by querying Wikipedia and summarizing answers with GPT-3

# Setup

```bash
export OPENAI_API_KEY=<PASTE YOUR OPENAI API KEY HERE>
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

# Usage

```
> python main.py

Welcome to Wikipedia GPT-3 Bot. Ask any question.

(wikibot) Who made Stable Diffusion?
Pulling up page: Stable Diffusion


    URL: https://en.wikipedia.org/wiki/Stable_Diffusion

    Context:

    > [...]  detailed images conditioned on text descriptions, though it can also be applied to other tasks such as inpainting, outpainting, and generating image-to-image translations guided by a text prompt.Stable Diffusion is a latent diffusion model, a variety of deep generative neural network developed by the CompVis group at LMU Munich. The model has been released by a collaboration of Stability AI, CompVis LMU, and Runway with support from EleutherAI and LAION. In October 2022, Stability AI raised $101 million dollars in a roun  [...]

    Answer: Stable Diffusion was made by a collaboration of Stability AI, CompVis LMU, and Runway with support from EleutherAI and LAION.


(wikibot) When did Liz Truss resign?
Pulling up page: Liz Truss


    URL: https://en.wikipedia.org/wiki/Liz_Truss

    Context:

    > [...] lic sector organisations. Her government announced large-scale borrowing and various tax cuts in a mini-budget, which led to financial instability, was widely criticised and was largely reversed. On 20 October 2022, amidst economic and political crisis, Truss announced her intention to resign as prime minister after 44 days in office, making her the shortest serving prime minister in the history of the UK. [...] of plans to cut taxes for people earning over £50,000. Consequently, it was thought she would be appointed chancellor of the Exchequer or business secretary, but she was instead promoted to  [...]

    Answer: Liz Truss resigned on 20 October 2022.


(wikibot) How big is the iPhone 14?
Pulling up page: IPhone 14


    URL: https://en.wikipedia.org/wiki/IPhone_14

    Context:

    > [...] 3 and iPhone 13 Mini, and were announced at the Apple Event in Apple Park in Cupertino, California on September 7, 2022, alongside the higher-priced iPhone 14 Pro and iPhone 14 Pro Max flagships. The iPhone 14 and iPhone 14 Plus feature a 6.1-inch (15 cm) and 6.7-inch (17 cm) display, improvements to the rear-facing camera, and satellite connectivity. The iPhone 14 was made available on September 16, 2022 and iPhone 14 Plus was made available on October 7, 2022 respectively,   [...]

    Answer: The iPhone 14 has a 6.1-inch display.

(wikibot)
```
