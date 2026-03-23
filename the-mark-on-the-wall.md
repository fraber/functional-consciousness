The Mark On The Wall

The text for this analysis was selected quite randomly, asking ChatGPT
for a short text in the public domain that would mainly consist of a
stream of consciousness.

The analysis of the text excerpts and therefore the list of self-models
is based on the SBR (Scene Based Reasoning) cognitive architecture
\[Bergmann Fenton 2015\]. However, this cognitive architecture has many
parallels with other cognitive architectures used in the context of the
AGI conference, so that this analysis should be understandable with a
general background of cognitive architectures.

An important part of SBR is the position of the episodic memory
("episody"), that records the performance of any past actions of the
agent. Even directing attention or searching for the timestamp of some
past event are considered "actions".

In the analysis we first show an entire paragraph of the text, followed
by the various parts of the paragraph that point to the use of a
self-model.

1\. PERHAPS IT WAS the middle of January in the present year that I
first looked up and saw the mark on the wall. In order to fix a date it
is necessary to remember what one saw. So now I think of the fire; the
steady film of yellow light upon the page of my book; the three
chrysanthemums in the round glass bowl on the mantelpiece.

+------+-------------------+-------------------+-------------------+
| 1.1  | "PERHAPS IT WAS   | ****Episody       | Determining the   |
|      | the middle of     | ****with time     | timestamp of some |
|      | January in the    | awareness****     | past event        |
|      | present year that |                   | implies an        |
|      | I \<did           |                   | episodic memory   |
|      | something\>"      |                   | of actions        |
|      |                   |                   | ("looking up" as  |
|      |                   |                   | a physical        |
|      |                   |                   | movement to       |
|      |                   |                   | direct the        |
|      |                   |                   | attention         |
|      |                   |                   | somewhere)        |
+------+-------------------+-------------------+-------------------+
|      | "I first looked   | ****attention**** | Directing         |
|      | up"               |                   | attention         |
|      |                   |                   | somewhere by      |
|      |                   |                   | physically moving |
|      |                   |                   | the head          |
+------+-------------------+-------------------+-------------------+
| 1.2a | "In order to fix  | ****episody****   | The phrase talks  |
|      | a date it is      |                   | about the process |
|      | necessary to      |                   | to determine the  |
|      | remember what one |                   | timestamp of some |
|      | saw."             |                   | past action. So   |
|      |                   |                   | it presupposes a  |
|      |                   |                   | model of past     |
|      |                   |                   | actions across    |
|      |                   |                   | time.             |
+------+-------------------+-------------------+-------------------+
| 1.2b | "In order to fix  | **                | Talks about how   |
|      | a date it is      | **performance**** | to determine the  |
|      | necessary to      |                   | timestamp of some |
|      | remember what one |                   | past action. It   |
|      | saw."             |                   | reflects on one   |
|      |                   |                   | factor ("remember |
|      |                   |                   | what one saw")    |
|      |                   |                   | that is important |
|      |                   |                   | for the           |
|      |                   |                   | performance of    |
|      |                   |                   | this search       |
|      |                   |                   | action -- to find |
|      |                   |                   | the action. So    |
|      |                   |                   | the phrase        |
|      |                   |                   | implies a model   |
|      |                   |                   | of the            |
|      |                   |                   | performance of    |
|      |                   |                   | the "to fix a     |
|      |                   |                   | data" action,     |
|      |                   |                   | i.e. to find the  |
|      |                   |                   | timestamp of the  |
|      |                   |                   | action.           |
+------+-------------------+-------------------+-------------------+
| 1.3  | "So now I think   | ****awareness**** | Observes the      |
|      | of the fire"      |                   | process of        |
|      |                   |                   | "thinking". We    |
|      |                   |                   | follow the        |
|      |                   |                   | Buddhist analysis |
|      |                   |                   | of an "inner      |
|      |                   |                   | sense" that       |
|      |                   |                   | allows a human to |
|      |                   |                   | "perceive" that   |
|      |                   |                   | mental processes  |
|      |                   |                   | are ongoing. So   |
|      |                   |                   | this sentence is  |
|      |                   |                   | equivalent to "So |
|      |                   |                   | now that I am     |
|      |                   |                   | moving"           |
+------+-------------------+-------------------+-------------------+
| 3    | "So now I think   | ****3D body pose  | Visual            |
|      | of the fire; the  | / spatial         | observation of    |
|      | steady film of    | awareness****     | objects and       |
|      | yellow light upon |                   | self-relative     |
|      | the page of my    |                   | position          |
|      | book; the three   |                   |                   |
|      | chrysanthemums in |                   | Spatial object    |
|      | the round glass   |                   | map / scene graph |
|      | bowl on the       |                   |                   |
|      | mantelpiece."     |                   |                   |
+------+-------------------+-------------------+-------------------+
| 4    | "\...the three    | ****Physical      | Distances and     |
|      | chrysanthemums in | position relative | relative          |
|      | the round glass   | to objects****    | positions of      |
|      | bowl on the       |                   | objects           |
|      | mantelpiece."     |                   |                   |
|      |                   |                   | Scene-relative    |
|      |                   |                   | coordinate system |
+------+-------------------+-------------------+-------------------+
| 5    | "the steady film  | ****Attention     | Sensory           |
|      | of yellow light   | focus /           | observation of    |
|      | upon the page of  | perceptual        | light and         |
|      | my book"          | monitoring****    | reflection        |
|      |                   |                   |                   |
|      |                   |                   | Attention pointer |
|      |                   |                   | linked to visual  |
|      |                   |                   | scene             |
+------+-------------------+-------------------+-------------------+

2\. Yes, it must have been the winter time, and we had just finished our
tea, for I remember that I was smoking a cigarette when I looked up and
saw the mark on the wall for the first time. I looked up through the
smoke of my cigarette and my eye lodged for a moment upon the burning
coals, and that old fancy of the crimson flag flapping from the castle
tower came into my mind, and I thought of the cavalcade of red knights
riding up the side of the black rock. Rather to my relief the sight of
the mark interrupted the fancy, for it is an old fancy, an automatic
fancy, made as a child perhaps. The mark was a small round mark, black
upon the white wall, about six or seven inches above the mantelpiece.

  ---- -------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------ --------------------------------------------------------- ----------------------------------
  6    "Yes, it must have been the winter time, and we had just finished our tea..."                                                                ****Time-awareness / episodic memory model****               Memory of recent events and seasonal context              Temporal memory index
  7    "...I remember that I was smoking a cigarette when I looked up and saw the mark on the wall for the first time."                             ****Attention focus / event-triggered memory****             Memory of simultaneous sensory and motor actions          Event-linked attention map
  8    "I looked up through the smoke of my cigarette and my eye lodged for a moment upon the burning coals"                                        ****Physical position relative to objects / gaze model****   Spatial position of self, object locations, visual path   Scene graph with gaze vector
  9    "...that old fancy of the crimson flag flapping from the castle tower came into my mind, and I thought of the cavalcade of red knights..."   ****Imagined scenario / predictive simulation model****      Visual memory and creative association                    Mental imagery tree
  10   "Rather to my relief the sight of the mark interrupted the fancy, for it is an old fancy, an automatic fancy, made as a child perhaps."      ****Attention focus / cognitive control model****            Competing thoughts and sensory input                      Attention priority map
  11   "The mark was a small round mark, black upon the white wall, about six or seven inches above the mantelpiece."                               ****3D body pose / spatial object model****                  Relative position of mark to self and furniture           Scene-relative coordinate system
  ---- -------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------ --------------------------------------------------------- ----------------------------------

3\. How readily our thoughts swarm upon a new object, lifting it a
little way, as ants carry a blade of straw so feverishly, and then leave
it\.... If that mark was made by a nail, it can\'t have been for a
picture, it must have been for a miniature---the miniature of a lady
with white powdered curls, powder-dusted cheeks, and lips like red
carnations. A fraud of course, for the people who had this house before
us would have chosen pictures in that way---an old picture for an old
room. That is the sort of people they were---very interesting people,
and I think of them so often, in such queer places, because one will
never see them again, never know what happened next. They wanted to
leave this house because they wanted to change their style of furniture,
so he said, and he was in process of saying that in his opinion art
should have ideas behind it when we were torn asunder, as one is torn
from the old lady about to pour out tea and the young man about to hit
the tennis ball in the back garden of the suburban villa as one rushes
past in the train.

  ---- --------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------- --------------------------------------------------------- -------------------------------------
  12   "How readily our thoughts swarm upon a new object, lifting it a little way, as ants carry a blade of straw so feverishly, and then leave it..."           ****Attention focus / thought mobility model****              Shifting mental attention between stimuli                 Attention map with temporal weights
  13   "If that mark was made by a nail, it can\'t have been for a picture, it must have been for a miniature..."                                                ****Prediction accuracy / hypothesis model****                Observation of mark and contextual inference              Probabilistic reasoning node
  14   "...the miniature of a lady with white powdered curls, powder-dusted cheeks, and lips like red carnations."                                               ****Imagined scenario / visual simulation model****           Memory of visual styles and creative reconstruction       Mental imagery tree
  15   "A fraud of course, for the people who had this house before us would have chosen pictures in that way---an old picture for an old room."                 ****Theory of mind / historical inference model****           Knowledge of past occupants and their aesthetic choices   Causal--intent network
  16   "...very interesting people, and I think of them so often, in such queer places, because one will never see them again, never know what happened next."   ****Memory availability / social-personal history model****   Episodic recall of people and imagined life paths         Episodic-social graph
  17   "...we were torn asunder, as one is torn from the old lady about to pour out tea and the young man about to hit the tennis ball in the back garden..."    ****Movement trajectory / imagined event model****            Recollection and simulation of simultaneous actions       Mental simulation tree
  ---- --------------------------------------------------------------------------------------------------------------------------------------------------------- ------------------------------------------------------------- --------------------------------------------------------- -------------------------------------

4\. But as for that mark, I\'m not sure about it; I don\'t believe it
was made by a nail after all; it\'s too big, too round, for that. I
might get up, but if I got up and looked at it, ten to one I shouldn\'t
be able to say for certain; because once a thing\'s done, no one ever
knows how it happened. Oh! dear me, the mystery of life; The inaccuracy
of thought! The ignorance of humanity! To show how very little control
of our possessions we have---what an accidental affair this living is
after all our civilization---let me just count over a few of the things
lost in one lifetime, beginning, for that seems always the most
mysterious of losses---what cat would gnaw, what rat would
nibble---three pale blue canisters of book-binding tools? Then there
were the bird cages, the iron hoops, the steel skates, the Queen Anne
coal-scuttle, the bagatelle board, the hand organ---all gone, and
jewels, too. Opals and emeralds, they lie about the roots of turnips.
What a scraping paring affair it is to be sure! The wonder is that I\'ve
any clothes on my back, that I sit surrounded by solid furniture at this
moment. Why, if one wants to compare life to anything, one must liken it
to being blown through the Tube at fifty miles an hour---landing at the
other end without a single hairpin in one\'s hair! Shot out at the feet
of God entirely naked! Tumbling head over heels in the asphodel meadows
like brown paper parcels pitched down a shoot in the post office! With
one\'s hair flying back like the tail of a race-horse. Yes, that seems
to express the rapidity of life, the perpetual waste and repair; all so
casual, all so haphazard\....

  ---- --------------------------------------------------------------------------------------------------------------------------------------- -------------------------------------------------------- ------------------------------------------------- ------------------------------
  18   "But as for that mark, I\'m not sure about it; I don\'t believe it was made by a nail after all; it\'s too big, too round, for that."   ****Prediction accuracy / hypothesis model****           Visual observation, uncertainty about cause       Probabilistic reasoning node
  19   "I might get up, but if I got up and looked at it, ten to one I shouldn\'t be able to say for certain..."                               ****Planning tree / action simulation model****          Consideration of potential actions and outcomes   Branching action tree
  20   "Oh! dear me, the mystery of life; The inaccuracy of thought! The ignorance of humanity!"                                               ****Confidence / uncertainty model****                   Reflection on cognitive limitations               Self-evaluation vector
  21   "...let me just count over a few of the things lost in one lifetime..."                                                                 ****Memory availability / episodic inventory model****   Recall of past possessions                        Episodic memory list
  22   "...three pale blue canisters of book-binding tools? Then there were the bird cages, the iron hoops, the steel skates..."               ****Memory availability / detailed recall model****      Objects previously owned                          Structured object list
  23   "...The wonder is that I\'ve any clothes on my back, that I sit surrounded by solid furniture at this moment."                          ****Physical / spatial self-model****                    Awareness of current body state and environment   Scene-relative spatial map
  24   "...being blown through the Tube at fifty miles an hour---landing at the other end without a single hairpin in one\'s hair!"            ****Movement trajectory / imagined path model****        Metaphorical visualization of rapid motion        Mental simulation trajectory
  25   "...Tumbling head over heels in the asphodel meadows like brown paper parcels..."                                                       ****Movement trajectory / imagined path model****        Imagined bodily motion in environment             Mental simulation trajectory
  26   "...all so casual, all so haphazard..."                                                                                                 ****Stress / uncertainty model****                       Cognitive reflection on unpredictability          Risk--uncertainty vector
  ---- --------------------------------------------------------------------------------------------------------------------------------------- -------------------------------------------------------- ------------------------------------------------- ------------------------------

5\. But after life. The slow pulling down of thick green stalks so that
the cup of the flower, as it turns over, deluges one with purple and red
light. Why, after all, should one not be born there as one is born here,
helpless, speechless, unable to focus one\'s eyesight, groping at the
roots of the grass, at the toes of the Giants? As for saying which are
trees, and which are men and women, or whether there are such things,
that one won\'t be in a condition to do for fifty years or so. There
will be nothing but spaces of light and dark, intersected by thick
stalks, and rather higher up perhaps, rose-shaped blots of an indistinct
colour---dim pinks and blues---which will, as time goes on, become more
definite, become---I don\'t know what\....

  ---- ---------------------------------------------------------------------- ----------------------------------------------- ----------------------------------------------------------------- ---------------------------------------------------------
  1    "The slow pulling down of thick green stalks..."                       ****Physical position relative to objects****   Visual--spatial relations between body, plants, and environment   Spatial scene graph (objects with relative coordinates)
  2    "The cup of the flower... deluges one with purple and red light."      ****Sensor model****                            Sensory input (light intensity, colour spectrum)                  Perceptual input buffer with uncertainty estimates
  3    "One... helpless, speechless, unable to focus one's eyesight."         ****Capability model****                        Motor and perceptual function states (speech, focus)              Capability schema with Boolean competence flags
  4    "Groping at the roots of the grass, at the toes of the Giants."        ****3D body pose****                            Body orientation, limb reach vectors                              3D skeletal pose representation
  5    "Which are trees, and which are men and women..."                      ****Knowledge completeness****                  Conceptual categories of perceived entities                       Semantic category map with known/unknown flags
  6    "That one won't be in a condition to do for fifty years or so."        ****Time-awareness****                          Temporal reasoning about future capability                        Temporal projection timeline
  7    "There will be nothing but spaces of light and dark..."                ****Sensor model****                            Visual field luminance distribution                               Visual field matrix or image map
  8    "Rose-shaped blots of an indistinct colour---dim pinks and blues..."   ****Prediction accuracy****                     Visual perception uncertainty and confidence level                Probabilistic percept map (e.g. Bayesian field)
  9    "Which will, as time goes on, become more definite..."                 ****Learning rate****                           Rate of perceptual refinement over time                           Learning curve tracker / adaptation rate function
  10   "Become---I don't know what..."                                        ****Confidence / uncertainty****                Epistemic self-assessment of knowledge limits                     Confidence variable / uncertainty distribution
  11   Entire imagined rebirth sequence                                       ****Goal hierarchy****                          Implicit goal of rebirth and perceptual self-formation            Nested goal tree (rebirth → perception → understanding)
  12   Entire passage ("Why, after all, should one not be born ther                                                                                                                             
  ---- ---------------------------------------------------------------------- ----------------------------------------------- ----------------------------------------------------------------- ---------------------------------------------------------

6\. And yet that mark on the wall is not a hole at all. It may even be
caused by some round black substance, such as a small rose leaf, left
over from the summer, and I, not being a very vigilant
housekeeper---look at the dust on the mantelpiece, for example, the dust
which, so they say, buried Troy three times over, only fragments of pots
utterly refusing annihilation, as one can believe.

  ---- ---------------------------------------------------------------- ----------------------------------------------- ---------------------------------------------------------------------------------- ------------------------------------------------------
  13   "That mark on the wall is not a hole at all."                    ****Prediction accuracy****                     Comparison between prior belief ("hole") and current visual evidence               Belief--evidence Bayesian update model
  14   "It may even be caused by some round black substance..."         ****Planning tree****                           Hypothetical reasoning and alternative explanations                                Branching hypothesis tree
  15   "Such as a small rose leaf, left over from the summer."          ****Knowledge completeness****                  Stored knowledge of likely objects and causes                                      Semantic knowledge base (object--context mapping)
  16   "I, not being a very vigilant housekeeper..."                    ****Self-observation model****                  Introspective self-evaluation of habits and behavior                               Self-trait memory / behavior log
  17   "Look at the dust on the mantelpiece, for example..."            ****Physical position relative to objects****   Spatial awareness of nearby furniture and surfaces                                 Scene graph with object nodes and spatial attributes
  18   "The dust which, so they say, buried Troy three times over..."   ****Memory availability****                     Retrieval of historical/cultural knowledge                                         Episodic and semantic memory retrieval structure
  19   "Only fragments of pots utterly refusing annihilation..."        ****Internal consistency****                    Integration of metaphor (ancient remains ↔ present dust) into coherent worldview   Conceptual coherence graph
  ---- ---------------------------------------------------------------- ----------------------------------------------- ---------------------------------------------------------------------------------- ------------------------------------------------------

7\. The tree outside the window taps very gently on the pane\.... I want
to think quietly, calmly, spaciously, never to be interrupted, never to
have to rise from my chair, to slip easily from one thing to another,
without any sense of hostility, or obstacle. I want to sink deeper and
deeper, away from the surface, with its hard separate facts. To steady
myself, let me catch hold of the first idea that passes\....
Shakespeare\.... Well, he will do as well as another. A man who sat
himself solidly in an arm-chair, and looked into the fire, so---A shower
of ideas fell perpetually from some very high Heaven down through his
mind. He leant his forehead on his hand, and people, looking in through
the open door,---for this scene is supposed to take place on a summer\'s
evening---But how dull this is, this historical fiction! It doesn\'t
interest me at all. I wish I could hit upon a pleasant track of thought,
a track indirectly reflecting credit upon myself, for those are the
pleasantest thoughts, and very frequent even in the minds of modest
mouse-coloured people, who believe genuinely that they dislike to hear
their own praises. They are not thoughts directly praising oneself; that
is the beauty of them; they are thoughts like this:

  ---- ------------------------------------------------------------------------------------------------------------------ -------------------------------------------------------------- --------------------------------------------------------- -----------------------------------------------------------------
  21   "The tree outside the window taps very gently on the pane."                                                        ****Physical position with relationship to other objects****   Auditory and visual spatial cues (tree, window, sound)    3D scene graph linking self-position to external sound source
  22   "I want to think quietly, calmly, spaciously..."                                                                   ****Goal self-model****                                        Desired cognitive and affective states                    Goal vector with emotional regulation parameters
  23   "Never to be interrupted, never to have to rise from my chair..."                                                  ****Planning of actions and environment****                    Anticipated physical movement and interruptions           Temporal action tree minimizing disturbance
  24   "To slip easily from one thing to another, without any sense of hostility, or obstacle."                           ****Meta-cognitive control model****                           Flow of associative thought and emotional smoothness      State-transition network of ideas with reduced friction weights
  25   "I want to sink deeper and deeper, away from the surface, with its hard separate facts."                           ****Abstract--concrete self-model gradient****                 Levels of conceptual abstraction and depth of cognition   Hierarchical depth map of conceptual focus
  26   "To steady myself, let me catch hold of the first idea that passes."                                               ****Attention control model****                                Stream of transient thoughts                              Dynamic buffer with selection/locking mechanism
  27   "Shakespeare... Well, he will do as well as another."                                                              ****Knowledge availability****                                 Cultural and literary memory recall                       Indexed semantic memory graph
  28   "A man who sat himself solidly in an arm-chair, and looked into the fire, so---"                                   ****Perspective simulation model****                           Imagined visual scene and physical pose of another        3D embodied simulation model
  29   "A shower of ideas fell perpetually from some very high Heaven down through his mind."                             ****Creative cognition model****                               Imagined source of ideas; symbolic mental flow            Metaphoric generative process graph
  30   "He leant his forehead on his hand, and people, looking in through the open door..."                               ****Social perspective-taking model****                        Simulated third-person observers; imagined viewpoints     Multi-agent scene model with observer nodes
  31   "But how dull this is, this historical fiction! It doesn't interest me at all."                                    ****Affective self-evaluation****                              Comparison between imagined content and felt interest     Reward prediction / affective mismatch register
  32   "I wish I could hit upon a pleasant track of thought, a track indirectly reflecting credit upon myself..."         ****Ego-reinforcement self-model****                           Self-concept and implicit self-esteem signals             Self-referential valuation loop
  33   "For those are the pleasantest thoughts, and very frequent even in the minds of modest mouse-coloured people..."   ****Empathy / social generalization model****                  Generalized model of others' inner experience             Statistical population-level belief schema
  34   "They are not thoughts directly praising oneself; that is the beauty of them..."                                   ****Self-deception / self-consistency model****                Rationalization of self-enhancing cognition               Cognitive dissonance minimization loop
  ---- ------------------------------------------------------------------------------------------------------------------ -------------------------------------------------------------- --------------------------------------------------------- -----------------------------------------------------------------

8\. \"And then I came into the room. They were discussing botany. I said
how I\'d seen a flower growing on a dust heap on the site of an old
house in Kingsway. The seed, I said, must have been sown in the reign of
Charles the First. What flowers grew in the reign of Charles the
First?\" I asked---(but I don\'t remember the answer). Tall flowers with
purple tassels to them perhaps. And so it goes on. All the time I\'m
dressing up the figure of myself in my own mind, lovingly, stealthily,
not openly adoring it, for if I did that, I should catch myself out, and
stretch my hand at once for a book in self-protection. Indeed, it is
curious how instinctively one protects the image of oneself from
idolatry or any other handling that could make it ridiculous, or too
unlike the original to be believed in any longer. Or is it not so very
curious after all? It is a matter of great importance. Suppose the
looking glass smashes, the image disappears, and the romantic figure
with the green of forest depths all about it is there no longer, but
only that shell of a person which is seen by other people---what an
airless, shallow, bald, prominent world it becomes! A world not to be
lived in. As we face each other in omnibuses and underground railways we
are looking into the mirror; that accounts for the vagueness, the gleam
of glassiness, in our eyes. And the novelists in future will realize
more and more the importance of these reflections, for of course there
is not one reflection but an almost infinite number; those are the
depths they will explore, those the phantoms they will pursue, leaving
the description of reality more and more out of their stories, taking a
knowledge of it for granted, as the Greeks did and Shakespeare
perhaps---but these generalizations are very worthless. The military
sound of the word is enough. It recalls leading articles, cabinet
ministers---a whole class of things indeed which as a child one thought
the thing itself, the standard thing, the real thing, from which one
could not depart save at the risk of nameless damnation. Generalizations
bring back somehow Sunday in London, Sunday afternoon walks, Sunday
luncheons, and also ways of speaking of the dead, clothes, and
habits---like the habit of sitting all together in one room until a
certain hour, although nobody liked it. There was a rule for everything.
The rule for tablecloths at that particular period was that they should
be made of tapestry with little yellow compartments marked upon them,
such as you may see in photographs of the carpets in the corridors of
the royal palaces. Tablecloths of a different kind were not real
tablecloths. How shocking, and yet how wonderful it was to discover that
these real things, Sunday luncheons, Sunday walks, country houses, and
tablecloths were not entirely real, were indeed half phantoms, and the
damnation which visited the disbeliever in them was only a sense of
illegitimate freedom. What now takes the place of those things I wonder,
those real standard things? Men perhaps, should you be a woman; the
masculine point of view which governs our lives, which sets the
standard, which establishes Whitaker\'s Table of Precedency, which has
become, I suppose, since the war half a phantom to many men and women,
which soon, one may hope, will be laughed into the dustbin where the
phantoms go, the mahogany sideboards and the Landseer prints, Gods and
Devils, Hell and so forth, leaving us all with an intoxicating sense of
illegitimate freedom---if freedom exists\....

  ---- ------------------------------------------------------------------------------------------------------------- ------------------------------------------------------- ---------------------------------------------------------------- --------------------------------------------------------
  35   "And then I came into the room. They were discussing botany."                                                 ****Episodic memory self-****model****                  Recollection of spatial and social scene                         Temporal--spatial event map
  36   "I said how I'd seen a flower growing on a dust heap\..."                                                     ****Narrative self-model****                            Reconstructed autobiographical story                             Sequential narrative graph
  37   "The seed, I said, must have been sown in the reign of Charles the First."                                    ****Historical imagination model****                    Temporal extrapolation and symbolic projection                   Time-axis simulation with associative linkages
  38   "What flowers grew in the reign of Charles the First?\... (but I don't remember the answer)"                  ****Memory completeness and retrieval failure****       Attempted semantic recall                                        Memory retrieval node with null result
  39   "All the time I'm dressing up the figure of myself in my own mind..."                                         ****Ego-construction model****                          Self-image composition, identity aesthetics                      Recursive self-representation stack
  40   "Lovingly, stealthily, not openly adoring it..."                                                              ****Affective regulation of self-image****              Emotional modulation toward the self                             Feedback loop between admiration and inhibition
  41   "For if I did that, I should catch myself out, and stretch my hand at once for a book in self-protection."    ****Self-monitoring and corrective regulation****       Meta-awareness of self-praise leading to behavioral correction   Self-evaluation circuit triggering compensatory action
  42   "How instinctively one protects the image of oneself from idolatry\..."                                       ****Self-coherence preservation****                     Protection of consistent identity model                          Stability maintenance process for self-schema
  43   "Suppose the looking glass smashes, the image disappears..."                                                  ****Self-model fragility / self-dissolution model****   Visualization of identity loss via mirror metaphor               Dual self-representation (subject ↔ reflection)
  44   "Only that shell of a person which is seen by other people\..."                                               ****Social self-model (public persona)****              External perspective on self as seen by others                   Other-agent perception model
  45   "As we face each other in omnibuses and underground railways we are looking into the mirror..."               ****Collective reflective model****                     Interpersonal mirroring of inner states                          Distributed social network of mutual perception
  46   "Not one reflection but an almost infinite number; those are the depths they will explore."                   ****Multiplicity of self-models****                     Parallel reflective identities / perspectives                    Recursive reflection hierarchy or mirror graph
  47   "Leaving the description of reality more and more out of their stories..."                                    ****Epistemic simplification model****                  Prioritization of inner over external data                       Abstraction filter reducing sensory detail
  48   "The military sound of the word \['generalization'\] is enough."                                              ****Linguistic affect model****                         Sensory--emotional reaction to word associations                 Semantic--affective mapping structure
  49   "It recalls leading articles, cabinet ministers..."                                                           ****Associative memory model****                        Automatic activation of linked concepts                          Spreading activation network
  50   "As a child one thought the thing itself, the standard thing, the real thing\..."                             ****Developmental belief model****                      Early cognitive schema of authority and truth                    Temporal belief history
  51   "Generalizations bring back somehow Sunday in London..."                                                      ****Episodic--semantic linkage model****                Blending abstract term with sensory past                         Cross-domain associative memory graph
  52   "There was a rule for everything\... although nobody liked it."                                               ****Social norm compliance model****                    Learned social scripts and behavior rules                        Rule-set schema of social expectations
  53   "Tablecloths of a different kind were not real tablecloths."                                                  ****Categorical rigidity model****                      Binary classification of real/unreal objects                     Categorical ontology with strict inclusion rules
  54   "How shocking, and yet how wonderful it was to discover that these real things\... were not entirely real."   ****Reality-evaluation model****                        Reassessment of ontological assumptions                          Reality gradient continuum
  55   "Were indeed half phantoms, and the damnation\... only a sense of illegitimate freedom."                      ****Revaluation of belief consequences****              Emotional reinterpretation of moral fear                         Valence inversion mechanism
  56   "What now takes the place of those things I wonder\...?"                                                      ****Cultural schema update model****                    Querying missing social standards                                Knowledge gap placeholder structure
  57   "Men perhaps, should you be a woman; the masculine point of view which governs our lives..."                  ****Gendered social-role model****                      Awareness of power and normative bias                            Social hierarchy graph
  58   "Which has become\... half a phantom to many men and women..."                                                ****Cultural self-model decay****                       Recognition of societal identity breakdown                       Temporal decay function on shared schema
  59   "Leaving us all with an intoxicating sense of illegitimate freedom---if freedom exists."                      ****Existential freedom model****                       Meta-reflection on autonomy vs. illusion                         Paradox graph (freedom ↔ phantom)
  ---- ------------------------------------------------------------------------------------------------------------- ------------------------------------------------------- ---------------------------------------------------------------- --------------------------------------------------------

9\. In certain lights that mark on the wall seems actually to project
from the wall. Nor is it entirely circular. I cannot be sure, but it
seems to cast a perceptible shadow, suggesting that if I ran my finger
down that strip of the wall it would, at a certain point, mount and
descend a small tumulus, a smooth tumulus like those barrows on the
South Downs which are, they say, either tombs or camps. Of the two I
should prefer them to be tombs, desiring melancholy like most English
people, and finding it natural at the end of a walk to think of the
bones stretched beneath the turf\.... There must be some book about it.
Some antiquary must have dug up those bones and given them a name\....
What sort of a man is an antiquary, I wonder? Retired Colonels for the
most part, I daresay, leading parties of aged labourers to the top here,
examining clods of earth and stone, and getting into correspondence with
the neighbouring clergy, which, being opened at breakfast time, gives
them a feeling of importance, and the comparison of arrow-heads
necessitates cross-country journeys to the county towns, an agreeable
necessity both to them and to their elderly wives, who wish to make plum
jam or to clean out the study, and have every reason for keeping that
great question of the camp or the tomb in perpetual suspension, while
the Colonel himself feels agreeably philosophic in accumulating evidence
on both sides of the question. It is true that he does finally incline
to believe in the camp; and, being opposed, indites a pamphlet which he
is about to read at the quarterly meeting of the local society when a
stroke lays him low, and his last conscious thoughts are not of wife or
child, but of the camp and that arrowhead there, which is now in the
case at the local museum, together with the foot of a Chinese murderess,
a handful of Elizabethan nails, a great many Tudor clay pipes, a piece
of Roman pottery, and the wine-glass that Nelson drank out of---proving
I really don\'t know what.

  ---- --------------------------------------------------------------------------------------------------------------------- ---------------------------------------------- ------------------------------------------------ --------------------------------------------------
  60   "In certain lights that mark on the wall seems actually to project from the wall."                                    ****Perceptual inference model****             Visual contrast, light variation                 Depth map reconstruction
  61   "Nor is it entirely circular. I cannot be sure, but it seems to cast a perceptible shadow..."                         ****Uncertainty estimation model****           Sensory evidence evaluation                      Bayesian perceptual confidence field
  62   "If I ran my finger down that strip of the wall it would, at a certain point, mount and descend a small tumulus..."   ****Imagined sensorimotor model****            Kinesthetic simulation of touch                  Predictive body schema simulation
  63   "Like those barrows on the South Downs..."                                                                            ****Analogy generation model****               Visual--conceptual comparison                    Cross-domain mapping (wall → landscape)
  64   "Of the two I should prefer them to be tombs, desiring melancholy like most English people..."                        ****Affective preference self-model****        Emotional tendencies and cultural association    Valence bias vector (melancholy preference)
  65   "Finding it natural at the end of a walk to think of the bones stretched beneath the turf..."                         ****Habitual reflective model****              Cultural and personal cognitive ritual           Temporal habit schema
  66   "There must be some book about it."                                                                                   ****Knowledge search model****                 Expectation of external information              Query node in epistemic graph
  67   "Some antiquary must have dug up those bones and given them a name..."                                                ****Inference of others' mental models****     Imagined intentions and actions of experts       Theory-of-mind simulation node
  68   "What sort of a man is an antiquary, I wonder?"                                                                       ****Personality simulation model****           Prototype generation based on social roles       Attribute inference graph
  69   "Retired Colonels for the most part, I daresay..."                                                                    ****Stereotypical social model****             Sociocultural type knowledge                     Schema-based classifier (occupation/personality)
  70   "Leading parties of aged labourers to the top here, examining clods of earth and stone..."                            ****Scenario imagination model****             Spatio-temporal narrative construction           Event simulation sequence
  71   "Getting into correspondence with the neighbouring clergy..."                                                         ****Social interaction model****               Communication rituals and social validation      Network of relational exchanges
  72   "Which, being opened at breakfast time, gives them a feeling of importance..."                                        ****Emotional attribution model****            Inferred affective reward of another person      Affective reward mapping
  73   "The comparison of arrow-heads necessitates cross-country journeys..."                                                ****Planning simulation of another agent****   Projected sequences of actions and motivations   Action--goal tree for imagined subject
  74   "An agreeable necessity both to them and to their elderly wives..."                                                   ****Social empathy model****                   Shared domestic motivations and subtle irony     Joint-utility function with emotional overlay
  75   "While the Colonel himself feels agreeably philosophic in accumulating evidence..."                                   ****Cognitive self-image projection****        Model of another's self-concept                  Metacognitive attribution graph
  76   "It is true that he does finally incline to believe in the camp..."                                                   ****Belief-formation model****                 Evidence accumulation over time                  Weighted evidence network
  77   "And, being opposed, indites a pamphlet..."                                                                           ****Communicative intention model****          Motivation to persuade or defend belief          Argument structure with author node
  78   "Which he is about to read at the quarterly meeting of the local society when a stroke lays him low..."               ****Mortality and terminal self-model****      Simulation of final consciousness                Temporal boundary model (life timeline)
  79   "His last conscious thoughts are not of wife or child, but of the camp and that arrowhead there..."                   ****Goal persistence model****                 Fixed-point attention at death                   Priority-weighted goal graph
  80   "Which is now in the case at the local museum, together with the foot of a Chinese murderess..."                      ****Cultural memory archive model****          Collective storage of symbolic artifacts         Museum-like associative data repository
  81   "Proving I really don't know what."                                                                                   ****Epistemic humility model****               Acknowledgment of cognitive limits               Confidence decay / uncertainty node
  ---- --------------------------------------------------------------------------------------------------------------------- ---------------------------------------------- ------------------------------------------------ --------------------------------------------------

10\. No, no, nothing is proved, nothing is known. And if I were to get
up at this very moment and ascertain that the mark on the wall is
really---what shall we say?---the head of a gigantic old nail, driven in
two hundred years ago, which has now, owing to the patient attrition of
many generations of housemaids, revealed its head above the coat of
paint, and is taking its first view of modern life in the sight of a
white-walled fire-lit room, what should I gain?---Knowledge? Matter for
further speculation? I can think sitting still as well as standing up.
And what is knowledge? What are our learned men save the descendants of
witches and hermits who crouched in caves and in woods brewing herbs,
interrogating shrew-mice and writing down the language of the stars? And
the less we honour them as our superstitions dwindle and our respect for
beauty and health of mind increases\.... Yes, one could imagine a very
pleasant world. A quiet, spacious world, with the flowers so red and
blue in the open fields. A world without professors or specialists or
house-keepers with the profiles of policemen, a world which one could
slice with one\'s thought as a fish slices the water with his fin,
grazing the stems of the water-lilies, hanging suspended over nests of
white sea eggs\.... How peaceful it is down here, rooted in the centre
of the world and gazing up through the grey waters, with their sudden
gleams of light, and their reflections---if it were not for Whitaker\'s
Almanack---if it were not for the Table of Precedency!

  ---- ----------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------- ------------------------------------------------------ ---------------------------------------------------
  82   "No, no, nothing is proved, nothing is known."                                                                                      ****Epistemic humility / uncertainty model****      Meta-evaluation of knowledge claims                    Confidence decay node / uncertainty register
  83   "If I were to get up at this very moment and ascertain that the mark on the wall is really... the head of a gigantic old nail..."   ****Hypothetical sensorimotor model****             Imagined action and consequence                        Counterfactual action simulation tree
  84   "...owing to the patient attrition of many generations of housemaids, revealed its head above the coat of paint..."                 ****Temporal decay / persistence model****          Long-term environmental change                         Multi-generational temporal event sequence
  85   "...taking its first view of modern life in the sight of a white-walled fire-lit room..."                                           ****Object-perspective ****simulation model****     Attribution of "experience" to inanimate object        Perspective node with temporal context
  86   "What should I gain?---Knowledge? Matter for further speculation?"                                                                  ****Goal evaluation / knowledge utility model****   Expected outcome from an action                        Utility function with hypothetical gain
  87   "I can think sitting still as well as standing up."                                                                                 ****Action independence model****                   Equivalence of cognitive processing across postures    State-invariant cognition representation
  88   "And what is knowledge? What are our learned men save the descendants of witches and hermits...?"                                   ****Cultural epistemic model****                    Historical reasoning about knowledge production        Conceptual lineage graph
  89   "...interrogating shrew-mice and writing down the language of the stars?"                                                           ****Analogical reasoning model****                  Comparing past practices to contemporary knowledge     Cross-domain analogy graph
  90   "And the less we honour them as our superstitions dwindle and our respect for beauty and health of mind increases..."               ****Value re-evaluation model****                   Shifting internal valuation of knowledge and culture   Valence update on cultural hierarchy
  91   "Yes, one could imagine a very pleasant world. A quiet, spacious world, with the flowers so red and blue in the open fields."       ****Imagined environment self-model****             Sensory and affective simulation of a peaceful world   Multi-sensory imagined scene graph
  92   "A world without professors or specialists or house-keepers with the profiles of policemen..."                                      ****Social structure simulation model****           Abstracted societal roles and absence thereof          Simplified social network / schema filter
  93   "...a world which one could slice with one's thought as a fish slices the water..."                                                 ****Embodied imagination model****                  Kinesthetic simulation of mental traversal             Action--effect simulation in imagined environment
  94   "...hanging suspended over nests of white sea eggs..."                                                                              ****Spatial awareness in imagination****            3D perception of imagined space                        Volumetric scene model
  95   "...rooted in the centre of the world and gazing up through the grey waters..."                                                     ****Perspective and orientation self-model****      Imagined vantage point and relative depth              Ego-centric 3D coordinate mapping
  96   "...if it were not for Whitaker's Almanack---if it were not for the Table of Precedency!"                                           ****Constraint awareness model****                  Recognition of societal or institutional limits        Rule/constraint overlay on imagined scene
  ---- ----------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------- ------------------------------------------------------ ---------------------------------------------------

11\. I must jump up and see for myself what that mark on the wall really
is---a nail, a rose-leaf, a crack in the wood?

Here is nature once more at her old game of self-preservation. This
train of thought, she perceives, is threatening mere waste of energy,
even some collision with reality, for who will ever be able to lift a
finger against Whitaker\'s Table of Precedency? The Archbishop of
Canterbury is followed by the Lord High Chancellor; the Lord High
Chancellor is followed by the Archbishop of York. Everybody follows
somebody, such is the philosophy of Whitaker; and the great thing is to
know who follows whom. Whitaker knows, and let that, so Nature counsels,
comfort you, instead of enraging you; and if you can\'t be comforted, if
you must shatter this hour of peace, think of the mark on the wall.

I understand Nature\'s game---her prompting to take action as a way of
ending any thought that threatens to excite or to pain. Hence, I
suppose, comes our slight contempt for men of action---men, we assume,
who don\'t think. Still, there\'s no harm in putting a full stop to
one\'s disagreeable thoughts by looking at a mark on the wall.

  ----- ---------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------- --------------------------------------------------------- ----------------------------------------
  97    "I must jump up and see for myself what that mark on the wall really is---a nail, a rose-leaf, a crack in the wood?"               ****Hypothetical action / perceptual self-model****       Expected sensory input from action                        Counterfactual sensory prediction tree
  98    "Here is nature once more at her old game of self-preservation."                                                                   ****Agency attribution model****                          Observation of natural processes and inferred intent      Cause--effect simulation node
  99    "This train of thought... is threatening mere waste of energy, even some collision with reality"                                   ****Energy/effort estimation model****                    Cognitive cost vs. physical action                        Predictive effort cost map
  100   "Who will ever be able to lift a finger against Whitaker\'s Table of Precedency?"                                                  ****Constraint awareness / social hierarchy model****     Institutional rules and limitations                       Social dependency graph
  101   "The Archbishop of Canterbury is followed by the Lord High Chancellor; ... everybody follows somebody..."                          ****Social order / relational hierarchy model****         Knowledge of authority sequences                          Directed graph of social hierarchy
  102   "The great thing is to know who follows whom. Whitaker knows..."                                                                   ****Theory of mind / informational self-model****         Awareness of others' knowledge                            Meta-knowledge graph
  103   "Nature counsels, comfort you, instead of enraging you..."                                                                         ****Affective regulation / coping model****               Inference from external "agent" (Nature)                  Emotional feedback loop
  104   "...if you must shatter this hour of peace, think of the mark on the wall."                                                        ****Attention focus / grounding model****                 Redirecting cognition to a neutral stimulus               Focused attention pointer
  105   "I understand Nature\'s game---her prompting to take action as a way of ending any thought that threatens to excite or to pain."   ****Meta-cognitive self-regulation model****              Mapping internal thoughts to behavioral impulses          Thought--action predictive mapping
  106   "Slight contempt for men of action---men, we assume, who don\'t think."                                                            ****Social evaluation / role model self-model****         Comparison of own reflective style vs. others' behavior   Value-weighted social evaluation
  107   "Putting a full stop to one\'s disagreeable thoughts by looking at a mark on the wall."                                            ****Cognitive grounding / emotional anchoring model****   Sensory input as attention redirector                     Stimulus--response attention map
  ----- ---------------------------------------------------------------------------------------------------------------------------------- --------------------------------------------------------- --------------------------------------------------------- ----------------------------------------

12\. Indeed, now that I have fixed my eyes upon it, I feel that I have
grasped a plank in the sea; I feel a satisfying sense of reality which
at once turns the two Archbishops and the Lord High Chancellor to the
shadows of shades. Here is something definite, something real. Thus,
waking from a midnight dream of horror, one hastily turns on the light
and lies quiescent, worshipping the chest of drawers, worshipping
solidity, worshipping reality, worshipping the impersonal world which is
a proof of some existence other than ours. That is what one wants to be
sure of\.... Wood is a pleasant thing to think about. It comes from a
tree; and trees grow, and we don\'t know how they grow. For years and
years they grow, without paying any attention to us, in meadows, in
forests, and by the side of rivers---all things one likes to think
about. The cows swish their tails beneath them on hot afternoons; they
paint rivers so green that when a moorhen dives one expects to see its
feathers all green when it comes up again. I like to think of the fish
balanced against the stream like flags blown out; and of water-beetles
slowly raising domes of mud upon the bed of the river. I like to think
of the tree itself: first the close dry sensation of being wood; then
the grinding of the storm; then the slow, delicious ooze of sap. I like
to think of it, too, on winter\'s nights standing in the empty field
with all leaves close-furled, nothing tender exposed to the iron bullets
of the moon, a naked mast upon an earth that goes tumbling, tumbling,
all night long. The song of birds must sound very loud and strange in
June; and how cold the feet of insects must feel upon it, as they make
laborious progresses up the creases of the bark, or sun themselves upon
the thin green awning of the leaves, and look straight in front of them
with diamond-cut red eyes\.... One by one the fibres snap beneath the
immense cold pressure of the earth, then the last storm comes and,
falling, the highest branches drive deep into the ground again. Even so,
life isn\'t done with; there are a million patient, watchful lives still
for a tree, all over the world, in bedrooms, in ships, on the pavement,
lining rooms, where men and women sit after tea, smoking cigarettes. It
is full of peaceful thoughts, happy thoughts, this tree. I should like
to take each one separately---but something is getting in the way\....
Where was I? What has it all been about? A tree? A river? The Downs?
Whitaker\'s Almanack? The fields of asphodel? I can\'t remember a thing.
Everything\'s moving, falling, slipping, vanishing\.... There is a vast
upheaval of matter. Someone is standing over me and saying---

  ----- ---------------------------------------------------------------------------------------------------- ------------------------------------------------------------- ---------------------------------------------- -----------------------------------
  108   "I feel that I have grasped a plank in the sea; I feel a satisfying sense of reality..."             ****Stabilization / existential anchoring model****           Affective feedback from perceptual focus       Emotional equilibrium loop
  109   "Something definite, something real... worshipping solidity, worshipping reality..."                 ****Ontological validation model****                          Perception vs. conceptual abstraction          Hierarchical reality schema
  110   "Proof of some existence other than ours."                                                           ****External‑world inference model****                        Sensory continuity as evidence of non‑self     Causal inference graph
  111   "Wood is a pleasant thing to think about. It comes from a tree..."                                   ****Material continuity model****                             Knowledge of natural processes                 Object--origin chain
  112   "Trees grow, and we don't know how they grow."                                                       ****Knowledge‑limit self‑model****                            Awareness of epistemic boundaries              Knowledge boundary node
  113   "They grow, without paying any attention to us..."                                                   ****Perspective decentering / non‑anthropic model****         Imagined perception from outside the self      Third‑person world model
  114   "I like to think of the fish balanced against the stream like flags blown out..."                    ****Imaginative empathy model (with non‑human entities)****   Visual and kinesthetic imagery                 Cross‑species embodied simulation
  115   "I like to think of the tree itself: first the close dry sensation of being wood..."                 ****Material embodiment model****                             Kinesthetic projection into inanimate matter   Embodied simulation chain
  116   "On winter's nights... nothing tender exposed to the iron bullets of the moon..."                    ****Temporal / environmental survival model****               Seasonal and sensory memory                    Temporal cycle model
  117   "How cold the feet of insects must feel upon it..."                                                  ****Empathic sensory projection****                           Temperature and touch imagery                  Cross‑agent sensory map
  118   "Even so, life isn't done with... there are a million patient, watchful lives still for a tree..."   ****Persistence and ****reincarnation model****               Conceptual metaphor of material continuity     Recursive life‑cycle model
  119   "It is full of peaceful thoughts, happy thoughts, this tree."                                        ****Emotional reflection / projective model****               Projection of inner calm into object           Affect‑object mapping
  120   "I should like to take each one separately---but something is getting in the way... Where was I?"    ****Meta‑cognitive disruption model****                       Attention monitoring and memory recall         Attention‑pointer reset
  121   "What has it all been about?\... Everything's moving, falling, slipping, vanishing..."               ****Ontological dissolution model****                         Breakdown of conceptual coherence              Decaying identity field
  122   "There is a vast upheaval of matter. Someone is standing over me and saying---"                      ****External intrusion / re‑anchoring model****               External auditory/visual signal                Reality re‑binding event
  ----- ---------------------------------------------------------------------------------------------------- ------------------------------------------------------------- ---------------------------------------------- -----------------------------------

13\. \"I\'m going out to buy a newspaper.\"

\"Yes?\"

\"Though it\'s no good buying newspapers\.... Nothing ever happens.
Curse this war; God damn this war!\... All the same, I don\'t see why we
should have a snail on our wall.\"

Ah, the mark on the wall! It was a snail.

  ----- --------------------------------------------------------------------- --------------------------------------------------------- --------------------------------------- ---------------------------------------
  123   "'I'm going out to buy a newspaper.' / 'Yes?'"                        ****Social interaction / communication state****          Spoken exchange, turn-taking cues       Dialogue log / conversational buffer
  124   "'Though it's no good buying newspapers.... Nothing ever happens.'"   ****Prediction accuracy / expectation model****           Forecast of events from media input     Probabilistic expectation node
  125   "Curse this war; God damn this war!"                                  ****Emotional / stress estimation model****               Affective response to external events   Mood--stress state vector
  126   "All the same, I don't see why we should have a snail on our wall."   ****Cognitive anomaly detection model****                 Observation vs. expected object         Object--expectation comparison
  127   "Ah, the mark on the wall! It was a snail."                           ****Perceptual verification / attention focus model****   Direct sensory confirmation             Perceptual binding / sensory register
  ----- --------------------------------------------------------------------- --------------------------------------------------------- --------------------------------------- ---------------------------------------
