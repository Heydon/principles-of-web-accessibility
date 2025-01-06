# Principles Of Web Accessibility

_A set of high-level guiding principles for approaching design and remediation for an accessible web._

* [Help evil to fail](#help-evil-to-fail)
* [Perfection is the enemy](#perfection-is-the-enemy)
* [By default or death](#by-default-or-death)
* [Parity is paramount](#parity-is-paramount)
* [Design for implementation](#design-for-implementation)
* [Structure first](#structure-first)
* [Use your words](#use-your-words)
* [Tools are not identities](#tools-are-not-identities)
* [Less is less](#less-is-less)
* [Fishing, not fish](#fishing-not-fish)
* [No points for performance](#no-points-for-performance)
 
## Help evil to fail

Not everything inaccessible should be made accessible. If a product or application is inherently exploitative or addictive, trades in misinformation or hatred, or just makes the world worse, do not help it to succeed or avoid litigation. Proprietors of such products do not deserve _any_ customers or users, least of all disabled or otherwise marginalized ones (who may be disproportionately affected by their practices). Where you draw the line between acceptable and despicable is a question of personal morality. But drawing the line makes your offering as a practitioner coherent.

## Perfection is the enemy

Nothing is—nor can be—100% accessible. Anyone who claims their offering is completely accessible is a liar, or they don't understand accessibility, or both. Usually both. It's okay to deliver inaccessible work, so long as it’s _more_ accessible. Do what you can within the constraints given. If the constraints are unreasonable, challenge those first. You may not feel confident you are always the best person available for contributing to accessibility. The important thing is that you _are_ available. Don’t leave the work to absent (and nonexistent) accessibility superheroes. 

## By default or death

Accessibility fundamentally does not work as a plugin, add-on, or opt-in state. If an interface offers the option to _enable_ accessibility, it is inaccessible. A low-contrast switch that turns on high contrast? Game over. Categorically, accessibility overlay software does not and cannot work. Adding _accessibility stuff_ on top of _inaccessible stuff_ does not address what needs to be addressed. The specific features offered by such third-party interlopers are immaterial. Resist the ideology of _post hoc_ accessibility at all costs. A Minimum Viable Product (MVP) without accessibility is not—even minimally—viable. 

## Parity is paramount

The point is not to create a better experience, or even a good experience. It’s to ensure a _comparable_ experience between different people. Interfaces should not be challenging to some and not to others, but some interfaces are necessarily complex and some content is inherently esoteric. You do not get to choose who is interested in—or can cope with—what. If an image serves as a joke, the alternative text should not give the joke away or explain why it is funny. It should _tell the same joke by alternative means_. The joke may be offensive to some or inexplicable to others. These are shortcomings of _inclusivity_, not accessibility.

## Design for implementation

They say form should follow function. But most organizations design first and develop second. The design phase consists of purely graphical ideation and leaves too many implementation questions unanswered. Consequently, developers are encouraged to prioritize visual approximation over usability. Drag-and-drop interfaces need to be operable by keyboard. This means buttons need to be provided. Those buttons will need to appear in the so-called _design_. As an accessibility practitioner, you must contribute to high-level design. Because form must follow function and the function needs to be accessible.

## Structure first

A poorly structured interface can technically pass WCAG. A well-structured and intuitive interface can have multiple discrete WCAG errors. Chances are, the latter is more accessible to most. Automated accessibility tools are only really good at locating discrete errors. These may be helpful diagnostically, but you need to take a holistic view. What will confuse or overwhelm people? Where will people get tripped up? Don’t waste time ticking off individual success criteria when the underlying structure needs redesigning.

## Use your words

A considerable proportion of web accessibility is about providing text labels. Buttons, links, and inputs must all have labels. Page titles and headings are also important types of label. Status messages are critical for labelling state. Including a label may placate an automated accessibility testing rig, but the label’s _wording_ makes the real difference. Good writing cannot be automated. Artificial Intelligence cannot anticipate your intent. Develop your writing and editing skills or include writers and editors in your process.

## Tools are not identities

Disability is no more uniform than ability. Different screen reader users use different screen reader software in different ways for different reasons in different circumstances to meet different needs and preferences. That is, if they are using screen reader software at all. There is no persona that can adequately exemplify a screen reader user or their behaviour. There is no screen reader user who speaks for screen reader users. So don’t design for screen reader users (or any other fictionalized homogenous group). Design to support the capabilites of screen reader software. People cannot—and should not—be quantified, but inputs and outputs can and are.

## Less is less

The mantra _less is more_ is incorrect. Less is just less and that’s a good thing. Too much of interface engineering is done because others have done it or just to prove it can be done. Stop. The more we do, and the more complex the output becomes, the more likely it will fail. And not just by producing discrete errors and breakdowns; more importantly by resisting comprehension. Most components, in most cases, should just be content. Content should rarely be hidden behind a button. Turning headings, paragraphs, and lists into an accessible tab interface is not an enhancement. It’s a degradation with bragging rights.

## Fishing, not fish

Designing accessible products and interfaces starts with designing the organizations that deliver them. You can deliver accessible work today but who will do it tomorrow? Who or what might _undo_ it tomorrow? Accessible design might mean building a frontend team consisting of developers well-versed in the frontend. It might mean retiring a CMS that prohibits accessible output. It might mean briefing editorial staff in how to structure their content. If you’re fixing inaccessibility yourself, by yourself, your impact will quickly fade. 

## No points for performance

Companies tend to prioritize _looking_ like they are addressing accessibility over actually doing it. They hire accessibility professionals and don’t give them the necessary resources. They commission research with disabled participants and refuse to interpret the feedback. They pay for audits and don’t implement the recommendations. They tell you color contrast needs to be assessed but won’t budge on any color relating to their sacred brand. If you want to make a real difference, demand praxis in place of performance.
