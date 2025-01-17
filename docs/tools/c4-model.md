# C4 Model

There are many differnet audiences for diagrams and documentaion, all with differen interests.

    When drawing software architecture diagrams, think like a software developer.
    A common set of abstractions, is more important than common notation.

A `software system` is made up of one or more `Containers`, each of which contains one or more `components`, which in turn are implemented by one or more `code elements`.

**C4 model**

1. Overview first

   - `System context`
   - `Containers`

2. zoom & filter

   - `Components`

3. details on demband
   - `code` e.g. classes

## Notation

`titles`
sort and meaningful, include the `diagram type`, numberad if diagram order is important; for example:

>     **System context diagram** for Financial Risk system

    **[system context]** financail risk system.

`Layout`
sticky notes and index cards (e.g. CRC cards).
make a great substibute for hand-drawn boxes, especially if you don't have a whiteboard.

`Visual consistency`
try to be consitsten with notation and element positioning across diagrams.

`Acronyms`
Be wary of using acronyms, especailly those related to the business/domain that you wark in.

`Elements`
Start with simple boxes containg the element name, typem technology (if appropriate) and a description/responsibilities.

`lines`
favour uni-directional lines showing the most important dependenciies or data flow, with an annotaion to be explicit about the purpose ot the line and direction.

>     show both directions when the intents are different.
>     Beware of hiding the true story.
>     Add more words to make the intent explicit.

`key/legend`
Explain shapes, line styles, colours, borders, acronyms, etc...
event if your notation seems obvious!

Use shape, colour and size to complement a diagram that already makes sense.

Use icons to supplement text, not replace it.

Increase the **readability** of software archiecture diagrams, so they can stand alone.

Any narrative should complement the diagram rather than explain it.

### Notes

**Abstractions first, notation second**
Ensure that your team has a ubiquitous language to describe software architecture.
