# maf_snippets

A collection of Metrological Application Framework snippets for SublimeText

# How To Use
- clone this repository in your SublimeText User folder whose location varies depending on your OS:
  - Mac OS: ~/Library/Application Support/Sublime Text 2 or 3/Packages/User
  - Windows: User\AppData\Roaming\Sublime Text 2 or 3\Packages\User
- enter one of the snippets below anywhere in your .js file, press the Tab key on your keyboard and be efficient!

# Available snippets
MAF-specific snippets:
- mafhgrid - creates horizontal MAF.element.Grid instance
- mafvgrid - creates vertical MAF.element.Grid instance
- mafsub - shorthand for the function.subscribeTo clause
- mafunsubscribe - shorthand for the function.unsubscribe clause
- mafthemeset - shorthand for Theme.set clause
- maftextbtn - creates MAF.control.TextButton instance
- maftext - creates MAF.element.Text instance
- maftabs - creates MAF.control.TabStrip instance
- mafrequest - sends MAF.Request
- maflocal - shorthand for $_(“localizationKey”)
- mafloading - shorthand for MAF.utility.WaitIndicator.up()
- mafloaded - shorthand for MAF.utility.WaitIndicator.down()
- mafimg - creates MAF.element.Image instance
- mafcontainer - creates MAF.element.Container instance
- maffire - shorthand for the object.fire clause
- mafst - shorthand for "style: { }"
- mafstyle - shorthand for new style for MAF Themes
- mafevh - shorthand for empty EVent Handler function with single event argument
- mafcn - shorthand for the ClassName property
- mafvo - shorthand for vOffset property
- mafho - shorthand for hOffset property
- maflbl - shorthand for the label property (with localization-friendly value)
- mafmesfet - shorthand for MAF.messages.fetch(key_to_fetch)
- mafmessto - shorthand for MAF.messages.store(key_to_store, value)
- mafmesrem - shorthand for MAF.messages.remove(key_to_remove)
- mafslider - shorthand for MAF.SliderCarousel

Generic JS snippets:
- iffy - creates Immediately-Invoked Function Expression (IFFY)
- unif - creates if clause for checking whether typeof is undefined
- un - "undefined"
- clv - shorthand for the console.log directive with message and variable
- cl - shorthand for the console.log directive