# Description
The *Moral Vending Machine* is a project out of the [Critical Making Lab](http://criticalmaking.com/) at the University of Toronto. More information about this project, including build instructions for the hardware, will be available at this [project page](http://criticalmaking.com/moral-vending-machine).

# Original Abstract
The Blackbox Vending Machine is an interactive touchscreen-based kiosk that will ask conference participants to make a series of ethical, moral, social, and political decisions as part of a “maker culture express” experience. The name of this project satirizes the official slogan of Redbox (a company specializing in home media rentals via automated retail kiosks), which reads: “For one dollar, you buy 2 to 3 hours of happiness.” It is also a sendup of two common tropes we regularly encounter in our lab's 3D printing-related work: the Star Trek replicator, a media technofuture black box promising that we will one day be able to easily and unproblematically materialize everything, from earl grey tea to laser weapons, by rearranging subatomic particles at the command of a human voice; and the MakerBot Replicator 3D printer, the preeminent black box in emerging “maker” culture, which trades on a similar promise in its marketing. Finally, the title acknowledges “express” culture embedded in these boxes, each of which is positioned as a device of immediacy and impulse.

An initial prompt will present participants with an option to “make” one of either a 3D-printed gun or custom prosthetic. This decision will launch a cascading tree of binary choices that explore a range of implications for their selection, from design considerations (e.g. aesthetic-driven vs. instrumental) to labour questions (e.g. hacker/maker skill vs professional experience and tacit knowledge). At each stage, participants will have access to exploded and manipulable views of the digital object, forcing them to consider questions around materiality in processes that bring digitalia into material production chains. Running alongside this will be a commentary on the values assumed to underlie the decision to “make” a technology that is often bound up in narratives about transhumanist extension, postcolonial cultures of innovation, and technological empowerment; or one that is frequently wrapped in pronouncements about terrorism and surveillance on the one hand, and personal freedom and radical decentralization on the other. The series of binary choices will be designed in such a way that both “positive” and “negative” moral aspects of the decisions are presented, leaving participants on seemingly ambiguous ethical footing by the end.

Upon completion, the machine will ask participants whether they would like the object they have chosen to be made. If they select yes, a miniature copy of their desired object, packaged in a “vending machine bubble,” will be dispensed with a final call to reflection, asking participants to share (on a display alongside the machine) their experience of making decisions that are
* often in tension with narratives of consumer/user choice
* increasingly encapsulated or buried in contemporary startup culture
* imbricated in discussions about whether certain technologies are “evil” and others are “good”

They will also be asked to contribute to the dialogue around the supposed agentic capacities inherent in such technology assemblages, and to consider how this dialogue is implicated in wider discussions on engagement with science and technology at both the informal and institutional level.

# Rationale for Prompts
I am interested in technologies that circumvent geographic boundaries.

I am interested in how technologies unsettle notions of expertise.

I am interested in new knowledge practices and epistemic cultures.

I am interested in the production of customizable goods.

I am interested in disrupting institutional or legal authority.

# Arduino Setup
* We're using an Adafruit 2.8" TFT Touch Shield for Arduino with Resistive Touch Screen.
* Get the Adafruit [GFX](https://github.com/adafruit/Adafruit-GFX-Library) and [ILI9341](https://github.com/adafruit/Adafruit_ILI9341) libraries.
* Lots of comments in the code...

