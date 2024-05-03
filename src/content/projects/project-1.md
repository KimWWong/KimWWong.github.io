---
#title: 'Project 1'
#description: 'Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci'
#image:
#    url: '/GitHub.webp'
#    alt: 'GitHub wallpaper'
#worksImage1:
#    url: '/image-1.webp'
#    alt: 'first image of your project.'
#worksImage2:
#    url: '/image-2.webp'
#    alt: 'second image of your project.'
#platform: Web
#stack: Astro, JavaScript
#website: https://astro-milky-way.netlify.app/
#github: https://github.com/ttomczak3/Milky-Way

title: 'Seeing Intuitive Physics'
description: 'When viewing static scenes, do we extract the dynamic underlying physics? Even spontaneously?'
platform: Web
stack: Astro, JavaScript
website: https://astro-milky-way.netlify.app/
github: https://github.com/ttomczak3/Milky-Way
---

<p class="p2">The study of 'intuitive physics' really took off just from asking people questions just like these ones below:</p>
    <div style="text-align:center;">
        <img style="max-width: 100%;" class="figure" alt="figure" src="/physics-reasoning.png"/>
    </div>
<p class="p2">Classic work has demonstrated that most people <b>fail to answer correctly</b>. (If you didn't already know the answer, I've actually given you the correct answers in the image &mdash; the dotted arrows are all <i>incorrect</i> trajectories.) </p>
<p class="p2">And such effects generalize to real-world behavior: When asked to drop a ball (while walking) to hit a marked target on the floor, for example, many people release the ball when it is directly over the target, mistakenly predicting that it will fall straight down (McCloskey, 1983). There are two salient themes that emerge from this work:</p>
<p class="p2" style="text-indent: 1em"><b>(1)</b> People are often poor at reasoning about physics</p>
<p class="p2" style="padding-left: 1em"><b>(2)</b> Intuitive physics is centrally a matter of higher-level reasoning and decision-making
<p class="p2">And although some recent work in the computational modeling world is beginning to work away at theme 1 (finding the mind's weaknesses/strengths), <i>theme 2 remains unaddressed</i>.

<p class="p2"><b><u>The Current Projects</u></b></p>
<p class="p2">The work here illustrates how the two themes provide an incomplete picture of how physical regularities are incorporated into the human mind, and suggests that although people may often be <i>poor at reasoning</i> about physics, their visual percepts themselves reveal a surprising facility with physical principles. In short, we may often be poor at <b><i>thinking</i></b> about physics, but we may nevertheless also be better at <b><i>seeing</i></b> physics.
<p class="p2">We are able to disentangle reasoning from seeing for 2 reasons: (1) instead of asking participants direct questions about the physical property in question (e.g. "Is this tower unstable enough to fall down?"), we employed subtler performance-based measures, which observers cannot intentionally control, and (2) the physics of the scene were completely task-irrelevant (and in some cases, participants would have performed better if they ignored the physics entire).
<p class="p2">Here you will see studies of intuitive physics in not only rigid objects, but also soft materials such as cloth! </p>
<p></p>
<span class="badge badge--item">RELEVANT PAPERS</span>
<p class="p1">
    Wong, K. W., Bi, W., Soltani, A. A., Yildirim, I., & Scholl, B. J. (2023). Seeing soft materials draped over objects: A case study of intuitive physics in perception, attention, and memory. <b><i>Psychological Science</i></b>, <i>34</i>(1), 111-119.
    <a class="footer__link" href="https://doi.org/10.1177/09567976221109194" target="_blank">[DOI]</a>
</p>
<p></p><span class="badge badge--item">RELEVANT UNDER REVIEW</span>
<p class="p1">
    Bi, W., Shah, A. D., Wong, K. W., Scholl, B. J., & Yildirim, I. (<i>submitted</i>). Computational models reveal that intuitive physics underlies visual processing of soft objects.
    <details><summary>[Click to show abstract]</summary>
        <p class="p1">
        Computational explorations of human cognition have been especially successful when applied to visual perception. Existing models have primarily focused on rigid objects, emphasizing shapepreserving invariance to changes in viewpoint, lighting, object size, and scene context. Yet many objects in our everyday environments, such as cloths, are soft. This poses both quantitatively greater and qualitatively different challenges for models of perception, due to soft objects’ dynamic and high-dimensional internal structure — as in the changing folds and wrinkles of a cloth waving in the wind. Soft object perception is also correspondingly rich, involving novel properties such as stiffness. Here we explore the ability of different kinds of computational models to capture human visual perception of the physical properties of texture-equated cloths (e.g., their degrees of stiffness) that are undergoing different naturalistic transformations (e.g., falling vs. waving in the wind). Across visual matching tasks, both the successes and failures of human performance are well explained by <i>Woven</i> — a novel model that incorporates physics-based simulations to infer probabilistic representations of cloths. In contrast, competing models that are calibrated to equal performance as Woven on objective measures — including Woven ablations and a deep neural network — fail to capture human performance. We also confirm a novel prediction of Woven in additional analysis of our data. We suggest that humanlike machine vision may also require representations that transcend image features, and involve intuitive physics.
        </p>
    </details>

<p></p><span class="badge badge--item">RELEVANT PRESENTATIONS</span>
<p class="p1">
    Wong, K. W., Shah, A. D., & Scholl, B. J. (2024). 
    Unconscious intuitive physics: Prioritized breakthrough into visual awareness for physically unstable block towers.
    Talk to be given at the annual meeting of the <b><i>Vision Sciences Society</i></b>,
    5/18/24, St. Pete Beach, FL.
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        A central goal of perception and cognition is to predict how events in our local environments are likely to unfold: what is about to happen? And of course some of the most reliable ways of answering this question involve considering the regularities of physics. Accordingly, a great deal of recent research throughout cognitive science has explored the nature of ‘intuitive physics’. The vast majority of this work, however, has involved higher-level reasoning, rather than seeing itself—as when people are asked to deliberate about how objects might move, in response to explicit questions (“Will it fall?”). Here, in contrast, we ask whether the apprehension of certain physical properties of scenes might also occur *unconsciously*, during simple passive viewing. Moreover, we ask whether certain physical regularities are not just processed, but also visually *prioritized*—as when a tower is about to fall. Observers viewed block towers—some stable, some unstable—defined in terms of whether they would collapse as a result of external physical forces (such as gravity) alone. We used continuous flash suppression (CFS) to render the towers initially invisible: observers viewed them monocularly through a mirror haploscope, while a dynamic Mondrian mask was presented to their other eye. We then measured how long towers took to break through this interocular suppression, as observers indicated when they became visually aware of anything other than the mask. The results were clear and striking: unstable towers broke into visual awareness faster than stable towers. And this held even while controlling for other visual properties—e.g. while contrasting pairs of stable vs. unstable towers sharing the same convex hull, and differing only in the horizontal placement of a single block. This work shows how physical instability is both detected and prioritized, not only during overt deliberation, but also in unconscious visual processing.
        </p>
    </details>

<p class="p1">
    Shah, A. D., Wong, K. W., Ilker, Y., & Scholl, B. J. (2023).
    Perceiving precarity (beyond instability) in block towers.
    Poster presented at the annual meeting of the <b><i>Vision Sciences Society</i></b>, 
    5/23/21, Online.  
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        Intuitive physics has traditionally been associated with higher-level cognition, but recent work has also focused on the exciting possibility that properties such as physical stability may be rapidly and spontaneously extracted as a part of seeing itself &mdash; as when you look at a tower of blocks, and can appreciate at a glance that it is about to topple. Much of this work has contrasted towers that appear stable vs. unstable, in terms of whether they would fall as a result of external physical forces (such as gravity) alone. But the 'perception of physics' in block towers seems richer than a binary stable/unstable state. Even when a tower is (and appears to be) stable, for example, we might still readily perceive how precarious it is &mdash; in terms of how much force would be required in order to knock it over. Here we explored perceived 'precariousness' using change detection. Observers viewed pairs of block-tower images (one at a time, separated by a mask), and simply reported whether the second image was different. The towers were always stable, but could be differentially precarious. On More-Precarious trials, a single block was shifted slightly so that the tower became less resistant to falling (as quantified by physics-based simulations with variable amounts of spatial jitter). On corresponding Less-Precarious trials, that same block was shifted slightly so that the tower became more resistant to falling. We expected greater attention to (and memory for) changes that introduced a greater likelihood of collapse. But we obtained exactly the opposite pattern: observers were far better at detecting changes on Less-Precarious trials, compared to More-Precarious trials. We explore the possibility that this surprising result may be explained by the 'perception of history', in terms of appreciating how such towers were constructed in the first place.
        </p>
    </details>

<p class="p1">
    Bi, W., Shah, A. D. Wong, K. W., Scholl, B. J, & Yildirim, I. (2021).
    Perception of soft materials relies on physics-based object representations: Behavioral and computational evidence.
    Poster presented at the annual meeting of the <b><i>Vision Sciences Society</i></b>, 
    5/23/21, Online.  
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        When encountering objects, we readily perceive not only low-level properties (e.g., color and orientation), but also seemingly higher-level ones &mdash; some of which seem to involve aspects of physics (e.g., mass). Perhaps nowhere is this contrast more salient than in the perception of soft materials such as cloths: the dynamics of these objects (including how their three-dimensional forms vary) are determined by their physical properties such as stiffness, elasticity, and mass. Here we argue that the perception of cloths and their physical properties must involve not only image statistics, but also abstract object representations that incorporate "intuitive physics". We do so by exploring the ability to <i>generalize</i> across very different image statistics in both visual matching and computational modeling. Behaviorally, observers had to visually match the stiffness of animated cloths reacting to external forces and undergoing natural transformations (e.g. flapping in the wind, or falling onto the floor). Matching performance was robust despite massive variability in the lower-level image statistics (including those due to location and orientation perturbations) and the higher-level variability in both extrinsic scene forces (e.g., wind vs. rigid-body collision) and intrinsic cloth properties (e.g., mass). We then confirmed that this type of generalization can be explained by a computational model in which, given an input animation, cloth perception amounts to inverting a probabilistic physics-based simulation process. Only this model &mdash; and neither the alternatives relying exclusively on simpler representations (e.g., dynamic image features such as velocity coherence) nor alternatives based on deep learning approaches &mdash; was able to explain observed behavioral patterns. These behavioral and computational results suggest that the perception of soft materials is governed by a form of "intuitive physics" &mdash; an abstract, physics-based representation of approximate cloth mechanics that explains observed shape variations in terms of how unobservable properties determine cloth reaction to external forces.
        </p>
    </details>

<p class="p1">
    Wong, K. W., Bi, W., Yildirim, I., & Scholl, B. J. (2021). 
    Seeing cloth-covered objects: A case study of intuitive physics in perception, attention, and memory. 
    Poster presented at the annual meeting of the <b><i>Vision Sciences Society</i></b>, 
    5/23/21, Online.  
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        We typically think of intuitive physics in terms of high-level cognition, but might aspects of physics also be extracted during lower-level visual processing? In short, might we not only *think* about physics, but also *see* it? We explored this in the context of *covered* objects &mdash; as when you see a chair with a blanket draped over it. To successfully recover the underlying structure of such scenes (and determine which image components reflect the object itself), we must account for the physical interactions between cloth, gravity, and object &mdash; which govern not only the way the cloth may wrinkle and fold on itself, but also the way it hangs across the object's edges and corners. We explored this using change detection: Observers saw two images of cloth-covered objects appear quickly one after the other, and simply had to detect whether the two raw images were identical. On "Same Object" trials, the superficial folds and creases of the cloth changed dramatically, but the underlying object was identical (as might happen if you threw a blanket onto a chair repeatedly). On "Different Object" trials, in contrast, both the cloth and the underlying covered object changed. Critically, "Same Object" trials always had *greater* visual change than "Different Object" trials &mdash; in terms of both brute image metrics (e.g. the number of changed pixels) and higher-level features (as quantified by distance in vectorized feature-activation maps from relatively late layers in a convolutional neural network trained for object recognition [VGG16]). Observers were far better at detecting changes on "Different Object" trials, despite the lesser degree of overall visual change. Just as vision "discounts the illuminant" to recover the deeper property of reflectance in lightness perception, visual processing uses intuitive physics to "discount the cloth" in order to recover the deeper underlying structure of objects.
        </p>
    </details>





