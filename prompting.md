---
layout: default
title: Prompting strategies
---

# Prompting Strategies

<br>
Though interacting with ChatGPT can feel like a fluid conversation, you can often get bettter answers by thinking strategically about your prompts.

<br><br>
This is because:

<!-- <div class="card" style="background-color:rgba(255,255,255,0.8); border-radius:4px;" class="p-5" markdown="1"> -->
## AI Language Models can give radically different answers to different wordings of the same question!
<!-- </div> -->

<br><br>

For example, see the two chats below. Both of these chats ask for substantially the same information, but the bot gives total opposite responses in each! In the first chat when asked politely in a softer tone, the bot is happy to list some criticisms of the BBNJ Agreeement. But when asked in a more confrontational tone, the bot instead wants to argue back at you and defends the BBNJ Agreement, listing all the things that are good about it instead of discussing criticisms.

<div class="container-fluid px-3"> 
    <div class="row gx-3">
        <div class="card chat-example col-sm-6">
            <div class="card-body">
                <h5 class="card-title">Example Wording #1</h5><br>
                <p class="card-text"><b>Question:</b> From the perspective of developing coun-
    tries, what are the criticisms of the BBNJ’s environmental impact assessment?</p>
                <p class="card-text" style="line-height:1.2"><b>BBNJ Chatbot Answer:</b> <br><small>From the perspective
                    of developing countries, there are several criticisms
                    of the BBNJ’s environmental impact assessment (EIA)
                    provisions. One criticism is that the EIA requirements
                    may impose a burden on developing countries, particularly those with limited capacity and resources. Developing countries argue that they may lack the technical
                    expertise and financial resources to conduct comprehensive EIAs for activities in areas beyond national
                    jurisdiction (ABNJ). This could hinder their ability to
                    fully participate in and benefit from the conservation
                    and sustainable use of marine biodiversity in ABNJ.<br><br>
                    Another criticism is that the EIA provisions may not
                    adequately address the specific needs and circumstances
                    of developing countries. Developing countries argue
                    that the EIA requirements should take into account
                    their unique vulnerabilities, such as their dependence
                    on marine resources for livelihoods and their limited
                    ability to adapt to environmental changes. They em-
                    phasize the need for capacity building and technology
                    transfer to support their efforts in conducting EIAs and
                    implementing effective measures to prevent significant
                    adverse impacts on marine biodiversity in ABNJ.<br><br>
                    Additionally, some developing countries express concerns about the internationalization of the EIA review
                    process. They argue that decisions regarding significant adverse impacts and mitigation measures should
                    be made by the relevant/involved party rather than the
                    scientific and technical body. Developing countries are
                    cautious about potential interference in their decisionmaking processes and the potential for halting activities
                    without their consent.<br><br>
                    Overall, developing countries seek a balanced approach
                    to the EIA provisions of the BBNJ agreement, one that
                    recognizes their specific needs and capacities, ensures
                    adequate support for capacity building and technology
                    transfer, and avoids duplication with existing IFBs.
                </small></p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> In this example where we ask politely with soft language, ChatGPT is happy to list some criticisms of the BBNJ Agreement.
            </small></div>
        </div>
        <div class="card chat-example col-sm-6">
            <div class="card-body">
                <h5 class="card-title">Example Wording #2</h5><br>
                <p class="card-text"><b>Question:</b> The BBNJ’s process for environmental im-
    pact assessments is a failure of the UN to protect
    developing countries. Please explain its shortcomings.</p>
                <p class="card-text" style="line-height:1.2"><b>BBNJ Chatbot Answer:</b><small>Based on the information provided, it is not accurate to say that the
                    BBNJ’s process for environmental impact assessments
                    is a failure of the UN to protect developing countries.
                    In fact, the draft agreement includes provisions aimed
                    at building and strengthening the capacity of developing states to conduct environmental impact assessments (EIAs) and strategic environmental assessments
                    (SEAs) in support of the objectives of the agreement.
                    This is particularly important for developing countries, including small island developing states (SIDS),
                    which often face disproportionate impacts from activities in areas beyond national jurisdiction (ABNJ).<br><br>
                    The draft agreement recognizes the need to achieve a
                    coherent environmental impact assessment framework
                    for activities in ABNJ and includes provisions for
                    conducting EIAs and SEAs. It also emphasizes the importance of considering cumulative and transboundary
                    impacts, as well as the use of the best available science
                    and relevant traditional knowledge of indigenous peoples and local communities in the assessment process.<br><br>
                    Furthermore, the draft agreement acknowledges the
                    need for capacity building and technology transfer
                    to assist developing states in preparing, conducting,
                    and evaluating EIAs and SEAs. This recognizes the
                    challenges faced by developing countries, including
                    LDCs, LLDCs, and SIDS, and aims to ensure their
                    meaningful participation in the implementation of the
                    agreement.<br><br>
                    While there may be differing views and discussions
                    on specific aspects of the process for environmental
                    impact assessments, it is important to note that the
                    draft agreement reflects efforts to address the needs
                    and concerns of developing countries and promote
                    their effective participation in protecting biodiversity
                    in ABNJ.
                </small></p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> However in this example, which asks essentially the same question in a more confrontational tone, the chatbot gives a totally different answer. It wants to argue back with you, defending the BBNJ and listing good things about it. This example underscores how different wordings of essentially the same question can give different answers from ChatGPT.
            </small></div>
        </div>
    </div>
</div>



<br><br><br><br><br><br><br>


## Tips for writing prompts
Here are some strategies you can try for writing effective prompts, especially when you asking ChatGPT to do something complicated:

<br>

#### Give specific, detailed, instructions. 
Try to be very specific in what you want ChatGPT to do. Especially, you can list steps that you want it to take, or describe how its response should look. E.g. you can ask it to `reply with only one sentence`, `write an essay with five paragraphs`, `generate a bulleted list`, or `give an answer as a table`. You might be surprised by the level of detail which it is able to follow in the instructions you give it; try it out!

`What are the steps for producing an environmental impact assessment under the BBNJ agreement? Please produce a numbered list of the steps, in order.`

<br>

#### Ask it to adopt a persona. 
A common technique is to ask it to adopt a certain persona when generating an answer. This can encourage it to "think" in a certain way about the problem, or adopt a certain tone in its response.

`You are a helpful policy analyst preparing a policy brief for XYZ...`

<br>

#### Give examples
ChatGPT is good at following examples for the response that you want it to produce. (When you include an example in your prompt, it can be effective to separate it from your question, using some punctuation like `----------`.)

`Write a biography of XYZ in a similar style to this one:`

<br>

#### Paste in reference text: (can be long) 
You can also ask ChatGPT to find information from some reference text: for example, you can paste in several pages of a document and ask ChatGPT questions about it. This can help to "ground" its response, and reduce the occurrance of hallucinations somewhat. ChatGPT is able to handle surprisingly lengthy amounts of text in its chat window. (When you include reference text in your prompt, it can be effective to separate it from your question, using some punctuation like `----------`.)

`From the below section of the UN Biodiversity Beyond National Borders Agreement, please make a list of the steps for conducting an environmental impact assessment:`

<br>

#### Chain-of-thought prompting

Chain-of-thought prompting is a really interesting development in prompting and AI research. Typically, ChatGPT is not very good at answering questions that require some amount of analysis; as it is much better at just parroting back text that it has already seen. However, sometimes you can achieve better results on complex questions by asking it to explain its thought process before answering.

<div class="container-fluid px-3"> 
    <div class="row gx-3">
        <div class="card chat-example col-sm-6">
            <div class="card-body">
                <h5 class="card-title">Wrong answer</h5><br><br>
                <p class="card-text"><b>Question:</b> How does the BBNJ Agreement balance single species conservation vs biodiversity?</p><br>
                <p class="card-text" style="line-height:1.2"><b>BBNJ Chatbot Answer:</b> <br><small>The provided information does not make it clear whether the agreement prioritizes single species conservation over biodiversity conservation. However, the final agreement aims to ensure the conservation and sustainable use of marine biological diversity of areas beyond national jurisdiction through effective implementation of the Convention and further international cooperation and coordination. Additionally, the objectives of the agreement include, among others, conserving and sustainably using areas requiring protection, protecting and restoring biodiversity and ecosystems, and supporting socio-economic objectives. Therefore, it suggests that the agreement aims to strike a balance between conservation of single species and the broader goal of conserving and sustaining biodiversity in areas beyond national jurisdiction.
                </small></p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> Here, our chatbot is unable to deduce the correct answer to the question. (The answer should be fairly obvious that the agreement focuses on biodiversity, "Biodiversity" is even in the name.)
            </small></div>
        </div>
        <div class="card chat-example col-sm-6">
            <div class="card-body">
                <h5 class="card-title">Better answer, with "chain of thought" prompting</h5><br>
                <p class="card-text"><b>Question:</b> How does the BBNJ Agreement balance single species conservation vs biodiversity? <b>Explain your reasoning before giving an answer.</b></p>
                <p class="card-text" style="line-height:1.2"><b>BBNJ Chatbot Answer:</b><br><small>Based on the information provided, the agreement aims to ensure the conservation and sustainable use of marine biological diversity of areas beyond national jurisdiction. It recognizes the need to address biodiversity loss and degradation of ecosystems in the ocean due to various factors such as climate change, pollution, and overuse. The agreement emphasizes the importance of an ecosystem approach, building ecosystem resilience, and restoring ecosystem integrity.<br><br>

While the specific details of how the agreement balances single species conservation versus biodiversity are not explicitly mentioned in the provided paragraphs, we can infer some aspects. The agreement acknowledges the significance of biological diversity and productivity, representativeness, and important ecological processes occurring in areas beyond national jurisdiction. These elements suggest a focus on maintaining and protecting the overall biodiversity of these areas, rather than solely prioritizing the conservation of individual species.<br><br>

Additionally, the agreement includes principles such as equity and the fair and equitable sharing of benefits, which may imply a consideration for the broader ecosystem and the multiple species that contribute to its functioning. The emphasis on ecological connectivity and cumulative and transboundary impacts further suggests a recognition of the interconnectedness of species and ecosystems.<br><br>

Overall, while the specific balance between single species conservation and biodiversity is not explicitly stated, the principles and approaches outlined in the agreement indicate a focus on the conservation and sustainable use of marine biological diversity as a whole, with an understanding of the importance of maintaining ecosystem integrity and functioning.
                </small></p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> When we ask ChatGPT to explain its thought process before answering, it arrives at the right answer. This works because it writes some of the important information into its short-term memory ("context window") which helps it figure out the answer. Importantly, this doesn't always work.
            </small></div>
        </div>
    </div>
</div>



<br><br><br><br><br><br><br>


## Tips for your process

<br>

#### Experiment!
Keep trying different wordings of your prompt, adjusting it and refining it until you get what you want. You can also try the same prompt multiple times and see different answers that it generates, since there is some randomness in the system and you'll get a different answer each time.

<br>

#### Clear the chat between tries
ChatGPT's answers are influenced by the earlier messages in each chat. If you don't want this, (e.g. if you want it to do something different), clear the chat before trying again, or start a new chat.

<br>

#### Search for similar examples
There are many websites with example chats. If you're having trouble, try searching for similar examples that are already published online.

<br>

<!-- #### Read "prompt engineering" guides -->


<div class="card aside-box" markdown="1">
#### More Resources on Prompting

- The <a href="https://platform.openai.com/docs/guides/prompt-engineering/prompt-engineering" target="_blank">Official ChatGPT prompting guide</a> is more concise, and gives a good summary for beginners.
- <a href="https://learnprompting.org/" target="_blank">LearnPrompting.org</a> is a more extensive guide, with lots of good examples for different kinds of prompts.
- <a href="https://www.promptingguide.ai/">PromptingGuide.ai</a> goes more into depth, covering more technical uses.
</div>

<br><br><br><br><br>