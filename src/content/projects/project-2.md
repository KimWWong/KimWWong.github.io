---
#title: 'Project 2'
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

title: 'Spontaneous Visual Routines'
description: 'Navigational affordances meet visual routines: case studies in mazes and beyond'
platform: Web
stack: Astro, JavaScript
website: https://astro-milky-way.netlify.app/
github: https://github.com/ttomczak3/Milky-Way
---
<p class="p2"><b><u>What actually is a "Visual Routine"?</u></b></p>
<p class="p2">Visual processing usually seems both incidental and instantaneous.  (You see color, for example, without needing to <i>try</i>, and without any noticeable lag.)  There are, however, fascinating exceptions to this rule.  For example, take a moment to glance at this picture before moving on.</p>
    <div style="text-align:center;">
        <img style="max-width: 80%;" class="figure" alt="figure" src="/shoelaces.png"/>
    </div>
<p class="p2">Now consider some questions that could be asked about that picture (without looking back at it!)</p>
<p class="p2" style="text-indent: 1em"><b>(1)</b> What colors were in the picture?</p>
<p class="p2">You can probably answer that question immediately, from memory — indicating that this property was extracted even before you were asked the question, just as a part of natural viewing.</p>
<p class="p2">But what about this question: </p>
<p class="p2" style="padding-left: 1em"><b>(2)</b> Were the green tip and the blue tip part of the same shoelace, or two different shoelaces?  </p>
<p class="p2">You probably don’t know the answer yet, which indicates that this property was not extracted incidentally during natural viewing.  When you look back at the shoelace picture, of course, you can answer this question too — and you can do so merely by <i>looking</i> (i.e. even without using your finger to follow along a lace).  But notice that even here you can’t answer the question <i>immediately</i>: whereas you see the laces’ color seemingly instantaneously, seeing which tip goes with which seems to involve a process that is appreciably deliberate, dynamic, and temporally extended (as you mentally ‘trace’ from one tip to another).</p>
<p class="p2">These types of visual operations that underlies your ability to answer the which-tip-goes-with-which question has been termed <b>‘visual routines’</b> (Ullman, 1984, 1996), and visual routines contrast with other forms of perception precisely in terms of the two features highlighted in that example: they are often invoked <b>only on demand</b> (rather than always occurring automatically), and they are inherently, appreciably <b>dynamic</b>, such that these operations often take some appreciable time to be executed.</p>
<p class="p2">Not only has there been discussion of how visual routines may lie at the root of well-known visual processes such as: figure-ground relationships, containment (e.g. “Is it inside?”), and connectedness (e.g. “Are both points on the same contour?”), but they have been prominent enough to be reviewed in introductory textbooks (e.g. Palmer, 1999). </p>
<p class="p2"><b><u>The Current Project</u></b></p>
<p class="p2">The work here studies visual routines under a new lens, re-examining the assumptions that traditionally defined visual routines, and exploring new contexts where visual routines may operate.  (Spoiler: <i>mazes!</i>)</p>
    <div style="margin-left: 0em">
        <img height="200" class="figure" alt="figure" src="/visroutines-mazedemo-trans.png"/>
    </div>

<p></p><span class="badge badge--item">RELEVANT PUBLICATION</span>
<p class="p1">
    Wong, K. W., & Scholl, B. J. (2024). Spontaneous path tracing in task-irrelevant mazes: Spatial affordances trigger dynamic visual routines.
    <b><i>Journal of Experimental Psychology: General</i></b>. Advance online publication.
    <br><a class="footer__link" href="https://doi.org/10.1037/xge0001618" target="_blank">[DOI]</a> <a class="footer__link" href="/Wong-Scholl-JEPG.pdf" target="_blank">[PDF]</a>
</p>
    <details><summary>[Click to show abstract]</summary>
    <p>
    Given a maze (e.g. in a book of puzzles), you might solve it by drawing out paths with your pencil.  But even without a pencil, you might naturally find yourself mentally tracing along various paths.  This ‘mental path tracing’ may intuitively seem to depend on your (overt, conscious, voluntary) goal of wanting to get out of the maze, but might it also occur spontaneously —as a result of simply seeing the maze, via a kind of dynamic ‘visual routine’?  Here, observers simply had to compare the visual properties of two probes presented in a maze.  The maze itself was entirely task-irrelevant, but we predicted that simply seeing the maze’s visual structure would ‘afford’ incidental mental path tracing (à la Gibson).  Across four experiments, observers were slower to compare probes that were further from each other along the paths, even when controlling for lower-level properties (such as the probes’ brute linear separation, ignoring the maze ‘walls’).  These results also generalized beyond mazes, to other unfamiliar displays with task-irrelevant circular obstacles.  This novel combination of two prominent themes from our field — affordances and visual routines — suggests that at least some visual routines may not require voluntary goals; instead, they may operate in an automatic (incidental, stimulus-driven) fashion, as a part of visual processing itself.
    </p></details>

<p></p>
<span class="badge badge--item">RELEVANT PRESENTATIONS</span>
<p class="p1">
    Wong, K. W., & Scholl, B. J. (2023). 
    What memories are formed by dynamic 'visual routines'? 
    Poster presented at the annual meeting of the <b><i>Vision Sciences Society</i></b>, 
    5/22/23, St. Pete Beach, FL.  
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        You can readily see at a glance how two objects spatially relate to each other. But seeing how 20 objects all relate seems impossible, due to computational explosion (with 190 pairs). Such situations require <i>visual routines</i>: dynamic visual procedures that efficiently compute various properties 'on demand' -- e.g. whether two points lie on the same winding path, in a busy scene containing many points and paths ('path tracing'). Some surprisingly foundational questions about visual routines remain unexplored, including: what (if anything) remains in visual memory after the execution of a visual routine? Does path tracing result in a memory of the traced path itself? Or just of <i>whether</i> there was a path? Or nothing at all, after the moment has passed? We explored this for spontaneous path tracing in 2D mazes. Observers saw a maze in which two probes appeared in positions connected by a path. They were then shown two mazes, and had to select which was the initially presented maze. Across experiments, the incorrect maze could be (1) a Path-Obstruction maze, where a new contour blocked the initial inter-probe path; (2) an Irrelevant-Obstruction maze, where a new contour was introduced elsewhere; or (3) an Alternative-Path maze, where the same new Path-Obstruction contour was accompanied by the removal of an existing contour, providing an alternative inter-probe path. Performance on Path-Obstruction trials was much better than on Irrelevant-Obstruction trials (always controlling for lower-level contour properties across trial types). But Alternative-Path trials entirely eliminated this advantage. This suggests that a visual memory is formed by spontaneous path tracing, but that its content is not the path itself, but only <i>whether</i> a path existed. If visual routines exist to answer on-demand questions during perception, then the resulting memories may consist only of the answers themselves, and not the processing that generated them.        
        </p>
    </details>

<p class="p1">
    Wong, K. W., & Scholl, B. J. (2023). 
    Spatial affordances can automatically trigger dynamic visual routines: Spontaneous path tracing in task-irrelevant mazes.
    Talk presented at the annual meeting of the <b><i>Vision Sciences Society</i></b>, 
    5/14/23, St. Pete Beach, FL.  
</p>
    <details><summary>[Click to show abstract]</summary>
        <p>
        Visual processing usually seems both incidental and instantaneous. But imagine viewing a jumble of shoelaces, and wondering whether two particular tips are part of the same lace. You can answer this by looking, but doing so may require something dynamic happening in vision (as the lace is effectively 'traced'). Such tasks are thought to involve 'visual routines': dynamic visual procedures that efficiently compute various properties on demand, such as whether two points lie on the same curve. Past work has suggested that visual routines are invoked by observers' particular (conscious, voluntary) goals, but here we explore the possibility that some visual routines may also be automatically triggered by certain stimuli themselves. In short, we suggest that certain stimuli effectively <i>afford</i> the operation of particular visual routines (as in Gibsonian affordances). We explored this using stimuli that are familiar in everyday experience, yet relatively novel in human vision science: mazes. You might often solve mazes by drawing paths with a pencil -- but even without a pencil, you might find yourself tracing along various paths <i>mentally</i>. Observers had to compare the visual properties of two probes that were presented along the paths of a maze. Critically, the maze itself was entirely task-irrelevant, but we predicted that simply <i>seeing</i> the visual structure of a maze in the first place would afford automatic mental path tracing. Observers were indeed slower to compare probes that were further from each other along the paths, even when controlling for lower-level visual properties (such as the probes' brute linear separation, i.e. ignoring the maze 'walls'). This novel combination of two prominent themes from our field -- affordances and visual routines -- suggests that at least some visual routines may operate in an automatic (fast, incidental, and stimulus-driven) fashion, as a part of basic visual processing itself.
        </p>
    </details>
