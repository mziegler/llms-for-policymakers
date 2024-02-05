---
layout: default
title: Strengths and Weankesses for Policy Work
---

# Strengths and Weaknesses for Policy Work
AI Language Models (like ChatGPT) can have such fluent-feeling conversations that feel like you're talking to a human, and this sometimes makes it hard to figure out what its real capabilities and limitations are. In this page, we talk about some of their strengths and weaknesses as they relate to policymakers' work.

<br><br>

# Strengths

<br>

#### Rewriting and rephrasing
ChatGPT is great at rewriting and rephrasing information to match certain styles. For example, you can write out your ideas in an informal tone, and ask ChatGPT to rewrite them using formal language that would be suitable to present at a policy venue at the UN. (In academia, I have seen this be especially useful for researchers who don't have English as their first language.) Since formal writing can be very time-consuming, this formal-rephrasing strength might make it a little easier to participate in formal bodies like the UN.

`Please rewrite this paragraph to be more formal, suitable to go into an official policy brief:`

<br>

#### Generating boilerplate text
*"Boilerplate"* refers to text that is reused often with a little modification, like parts of contracts and statements, for example. ChatGPT can be great at writing these procedural documents that have many parts repeated; and there are already some products to help produce things with templates.

`Please write me a biography of this person, using the following template:`

<br>

#### Answering questions about specific details
ChatGPT is great at parroting back information that it has already seen in its training data, or in documents that you provide it. (It's not as good at answering quetions that require it to do its own analysis.) You can take advantage of this by asking it to find specific bits of information in big documents, for example. 

There are several ways to take advantage of this capability. If you're using a regular ChatGPT chat window, you can copy and paste lengthy documents right into the chat, and ask ChatGPT questions about them. If you're using ChatGPT plus, you can upload PDF's and Microsoft Word documents to ask questions about. Google's *NotebookLM* allows you to upload documents and have conversations with an AI chatbot about them, for free. You can also find specialized chatbots in the GPT Store (and elsewhere), which are connected to specialized databases of information.


<div class="container-fluid px-3"> 
    <div class="row gx-3">
        <div class="card chat-example col-sm-10">
            <div class="card-body">
                <h5 class="card-title">Example detail-oriented question</h5><br>
                <p class="card-text"><b>Question:</b>What are the modalities for sharing the monetary benefits from marine genetic resources in the UN BBNJ
agreement?</p>
                <p class="card-text"><b>BBNJ Chatbot Answer:</b> In the final draft of the UN BBNJ agreement,
the modalities for sharing monetary benefits from
marine genetic resources include milestone pay-
ments, royalties, and other forms as determined
by the Conference of the Parties (COP) based
on recommendations from the access and benefit-
sharing mechanism. The COP is responsible for
determining the rate of payments related to mon-
etary benefits. The payments are made through
a special fund established under Article 52 of
the agreement. The modalities may also include
payments or contributions related to the commer-
cialization of products, including a percentage of
the revenue from sales of products, and a tiered
fee paid on a periodic basis. If all efforts to reach
consensus have been exhausted, a decision shall
be adopted by a three-fourths majority of Parties
present and voting.</p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> This example is from the "BBNJ Question-Answering Bot," which searches for its answers in a datatbase of documents about the UN BBNJ Agreement. It is generally pretty good at these types of questions: finding a specific detail amid many pages of information.</small></div>
        </div>
    </div>
</div>

<br>

#### Summarization

ChatGPT (and similar models) are pretty good at summarizing lengthy documents into consise summaries. You can take advantage of this by uploading / pasting in long documents, or using data-connected chatbots, (as described above).

`Below, I have pasted a section of the UNEP's 2023 report on Methane emissions. Please write me a 3-paragraph summary of this information.`

<br>

#### Explaining topics for varying levels of expertise
ChatGPT is often pretty good at explaining complex topics in simple terms. This can be helpful for quickly getting up to speed on new topics. (Just be cautious that its answers are sometimes biased or sometimes have errors.    )

`Could you please explain the UNCLOS (the United Nations Convention on the Law of the Sea) in simple terms?`

<br><br><br><br><br>

# Weaknesses

<br><br>

#### Limited analysis capabilities
ChatGPT is great at repeating back information that it has seen somewhere, but it is not very good at answering questions that require it to do its own analysis. It might give you an answer, but it is hard to know why it answered the way that it did, or what is influencing it. 

<div class="container-fluid px-3"> 
    <div class="row gx-3">
        <div class="card chat-example col-sm-10">
            <div class="card-body">
                <h5 class="card-title">Example of analysis limitations</h5><br>
                <p class="card-text"><b>Question:</b>How does the agreement balance single species
conservation vs biodiversity?</p>
                <p class="card-text"><b>BBNJ Chatbot Answer:</b> The provided information does not
make it clear whether the agreement prioritizes sin-
gle species conservation over biodiversity conser-
vation. However, the final agreement aims to en-
sure the conservation and sustainable use of ma-
rine biological diversity of areas beyond national
jurisdiction through effective implementation of the
Convention and further international cooperation
and coordination. Additionally, the objectives of the
agreement include, among others, conserving and
sustainably using areas requiring protection, pro-
tecting and restoring biodiversity and ecosystems,
and supporting socio-economic objectives. There-
fore, it suggests that the agreement aims to strike
a balance between conservation of single species
and the broader goal of conserving and sustaining
biodiversity in areas beyond national jurisdiction.</p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> This example shows the a limitation
of the bot’s ability to analyze and reason: the correct
answer is that the BBNJ agreement prioritizes
biodiversity conservation. ("Biodiversity" is even
in the name of the agreement.) The bot is unable to
deduce this and instead it rambles in no particular
direction.<br><br>
This example also underscores how hard it is
for users to discern when a bot is doing its own
analysis or being influenced by something from its
training data or document database. If there were
a sentence in the model training data or BBNJ
documents that directly answered this question, the
bot would likely have just found it and confidently
repeated it as its own answer; which it did not have
in this case.<br><br>
This question asked the bot to make a value
judgement, and its failure also underscores how
it’s hard to know where the bots’ values come
from in such a case, or how it would be doing
such an analysis. Should it count the occurrences of
"biodiversity" vs "species?" Should it look for strong
language around "biodiversity" and "species?" Or
something else?</small></div>
        </div>
    </div>
</div>

<br><br><br>


#### Mixing up sources
Large language models like GPT are trained on patterns and information from tons of sources, but as it generates text, it is not good at knowing where any of this information came from.

You can ask ChatGPT to cite its sources, but **ChatGPT is notorious for making up citations!** It does not actually know where the information is from. It will make up realistic-looking article names, fake DOI numbers, and even attribute them to familiar authors who write on the topic. (This is because it is just trying to mimic patterns it has seen, to produce a plausible-looking answer.)

Policymakers often work on different versions of a draft document or policy instrument, and in our experiemtation, we saw that ChatGPT would frequently mix up information from the different versions, and struggles to distinguish between them.

<br><br>

#### Confusing legal vs. common language
Many terms and phrases have a specific meaning in policy contexts, different from their meaning in everyday conversation. In our experimentation we found that ChatGPT sometimes gave wrong answers because it confused these specific policy meanings with general everyday meanings.

<div class="container-fluid px-3"> 
    <div class="row gx-3">
        <div class="card chat-example col-sm-10">
            <div class="card-body">
                <h5 class="card-title">Example confusing policy language and everyday language</h5><br>
                <p class="card-text"><b>Question:</b>How does the agreement balance single species
conservation vs biodiversity?</p>
                <p class="card-text"><b>BBNJ Chatbot Answer:</b> The provided information does not
make it clear whether the agreement prioritizes sin-
gle species conservation over biodiversity conser-
vation. However, the final agreement aims to en-
sure the conservation and sustainable use of ma-
rine biological diversity of areas beyond national
jurisdiction through effective implementation of the
Convention and further international cooperation
and coordination. Additionally, the objectives of the
agreement include, among others, conserving and
sustainably using areas requiring protection, pro-
tecting and restoring biodiversity and ecosystems,
and supporting socio-economic objectives. There-
fore, it suggests that the agreement aims to strike
a balance between conservation of single species
and the broader goal of conserving and sustaining
biodiversity in areas beyond national jurisdiction.</p>
            </div>
            <div class="card-footer"><small><b>Commentary:</b> This example shows the a limitation
of the bot’s ability to analyze and reason: the correct
answer is that the BBNJ agreement prioritizes
biodiversity conservation. ("Biodiversity" is even
in the name of the agreement.) The bot is unable to
deduce this and instead it rambles in no particular
direction.<br><br>
This example also underscores how hard it is
for users to discern when a bot is doing its own
analysis or being influenced by something from its
training data or document database. If there were
a sentence in the model training data or BBNJ
documents that directly answered this question, the
bot would likely have just found it and confidently
repeated it as its own answer; which it did not have
in this case.<br><br>
This question asked the bot to make a value
judgement, and its failure also underscores how
it’s hard to know where the bots’ values come
from in such a case, or how it would be doing
such an analysis. Should it count the occurrences of
"biodiversity" vs "species?" Should it look for strong
language around "biodiversity" and "species?" Or
something else?</small></div>
        </div>
    </div>
</div>

<br><br><br>





#### Only knows what's documented: missing context

Much of what happens in international policy happens behind closed doors and is never documented. We see the final product at the end of a negotiation process, for example, but many of the important behind-the-scenes disagreements never find their way into the official documents. The polite decorum of some policymaking spaces like the UN has the effect of hiding some of the geopolitics: for example, after aguing all week in a meeting, a conference will write that they were "having lively discussions." This filtering affects the capabilities of AI language models, because they can only "know" about what is documented.

This selective documentation could disproportinately put developing States and other marginalized actors at a disadvantage. Many have argued that the structures of the UN tend to favor the mostly-Western powerful countries: official documents from UN negotiations tend to celebrate the successes, but not the complaints of other actors who lose out. AI tools relying on these documents could therefore end up further sweeping these issues under the rug.



