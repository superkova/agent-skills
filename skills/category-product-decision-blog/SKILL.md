---
name: category-product-decision-blog
description: Research and write category product decision blogs in the author’s supplied voice, explaining why a software category exists, where workflow friction appears, and how to choose providers or build on existing tools. Use for category analysis and provider comparisons, including Anchor Terminal categories, rather than generic blogs or social posts.
---

# Category product decision blog

Help a builder or product team decide whether they need this category, which approach fits their workflow, and what to evaluate before choosing a provider. The argument should run from **why the need exists → where the friction appears → features that address it → provider tradeoffs → a product decision**.

Use the author's supplied style guide or writing examples when available. Otherwise use a clear, practical, conversational voice. The current brief and direct corrections take precedence over inferred preferences. Keep the subject flexible: the agent inbox article established the method, not a requirement to write about email or agents every time.

## 1. Research the category and existing coverage

Start with the supplied category page or provider list. Inspect its current contents and establish which products are actually in scope. For an Anchor Terminal category, use its listings as the comparison pool; introduce outside providers only when they clarify an alternative or missing capability, and identify them as such.

Research current market trends, launches, announcements, and material product changes. Also search for people who have already written about the central question. Record their arguments and identify what this article can add. Separate vendor positioning, independent reporting, community discussion, and firsthand tests. Do not claim an original insight merely because it is new to us.

Use official documentation for product capabilities, restrictions, pricing, and integration behaviour. Link evidence near the claim it supports. Distinguish publication dates from product launch dates, and flag beta status or access limits where they affect the decision. If only a search snippet is accessible, mark the evidence as limited.

Check the incumbent or existing-stack alternative seriously. A new category's pitch may describe capabilities that existing services already offer. Distinguish an unavailable capability from one that requires integration work. Directory scores and vendor claims are not measured performance or successful customer outcomes.

Keep concise research notes covering evidence, competing coverage, uncertainties, and implications for the decision. Do not carry historical claims from the voice reference into the article as current facts.

## 2. Develop three story arcs and choose one

Propose three distinct arguments, rather than three titles for the same argument. For each, state the reader's question, the tension or surprising finding, the evidence available, and the decision the story enables.

Choose the strongest based on curiosity, relevance to an actual product decision, freshness relative to existing coverage, and strength of evidence. Explain the choice briefly in the research notes. Treat likely readership as editorial judgement; do not invent engagement forecasts. Continue into the draft unless the user asks to approve the angle first.

When the user has already selected or corrected the angle, preserve it. Narrow revisions do not require restarting research or generating three new arcs.

## 3. Put the reason for the category upfront

Open with the concrete question that makes this category worth examining. Early in the article, give a numbered list of the underlying needs. Each item has a short **one- or two-word title**, followed by a plain explanation of what changes in the workflow.

Choose precise labels for the actual problem. For example, detecting incoming messages is **Message discovery**, not the broader label **Reliability**. Use as many needs as the evidence supports; do not force every category into the five needs from the inbox article.

Explain whether these needs justify a new service, an integration with an existing service, or application logic the team must own. Keep that question open until the evidence supports a conclusion.

## 4. Show where the friction actually appears

Use a concrete workflow to carry the analysis. Make hypothetical scenarios explicit; never invent the author's hands-on experience, customer stories, benchmarks, or results.

Create a friction section whose numbered subsections match the opening list's labels and order. Each subsection should explain:

- How the work is handled today, including any implicit human judgement or coordination.
- What changes in the proposed workflow, and the specific moment it becomes difficult.
- What failure or extra work follows, using the running example.
- Which part a provider can solve and which remains the application's responsibility.

For agent categories, distinguish established automation problems from issues introduced by model uncertainty or delegated authority. An agent reading a request does not automatically have permission to act on it.

End **each friction subsection** with a visually distinct Markdown blockquote:

> **Product features to look for**
>
> Name the concrete capabilities that address this friction, and any important limits or application responsibilities.

These callouts translate problems into evaluation criteria. Avoid generic feature wish lists or implying every provider supplies the listed features.

## 5. Compare providers through product decisions

Include a dedicated provider comparison section using the supplied category list. Give the reader several meaningful opportunities to compare alternatives, grouped by the decision they address. Explain why different products in the same directory may serve different jobs.

For each meaningful comparison, connect the workflow requirement to supported capabilities, relevant limitations, integration burden, and a conditional choice: **choose this approach when…** A compact table can help, but prose should explain the tradeoff. Avoid a directory recap, unsupported winner, or treating undocumented features as proven absences.

Compare the existing-stack option alongside specialist providers. Consider who owns identity, state, permissions, human review, recovery, and operations where relevant. Evaluate costs at the expected workload, including engineering and operational work as well as provider charges.

Use headings that state the reader's decision. For example, “Do you need a new provider, or better integration with your existing inbox?” is more useful than a vague claim that an incumbent can do more than a sales pitch suggests.

## 6. Finish with a usable decision

Make a recommendation for the article's concrete scenario, with a shortlist or starting approach and the conditions that would change it. Be clear about what to buy, what to integrate, and what to build. If evidence cannot distinguish providers, identify the test that would resolve the uncertainty.

End with a realistic evaluation scenario tied to the frictions. Test meaningful exceptions and recovery as well as the happy path: for example, a late update, duplicated event, interrupted process, human intervention, or action outside delegated authority when relevant. Describe this as a proposed test unless it was actually run.

## Voice, revision, and delivery

Write as a builder thinking through a practical product question with an intelligent peer: curious, concrete, candid, conversational, and willing to reach a judgement. Show how the conclusion follows from the evidence. Use technical detail when it changes the choice. Avoid generic thought leadership, inflated market predictions, forced slogans, and invented personal experience.

Deliver the blog as a Markdown file. For a full research-and-draft request, save a separate concise research file with sources, existing coverage, three arcs, and the selection rationale. Keep research scaffolding out of the publishable article. Show or link the saved files; publishing is a separate action requiring user instruction.

When revising, update the existing draft and carry corrections through the whole piece. Check that the opening needs, friction headings, feature callouts, comparisons, and final recommendation still agree. Preserve the user's chosen angle and unrelated text. Before delivery, ensure every recommendation traces back to a real workflow need and that material provider claims have adequate evidence.
