# Dark Patterns Recognition (CMOS)

CMOS is a extension that detects and highlights dark patterns on shopping websites. It reads text on product pages of shopping websites, then identifies and classifies dark pattern text. These potential dark patterns are then highlighted, with a popup that identifies and explains the category that a given dark pattern belongs to. 

## Dark Patterns?
Dark patterns are design tricks used to influence the way users interact with software. While some dark patterns are harmless, like emphasizing signup buttons with color, others can be more malicious in problematic. In the context of online stores, dark patterns can be used to nudge buyers into buying items they might not need. For further information on dark patterns, check out [this website](https://darkpatterns.org).

## Tech Stack
The Extension front-end that scrapes the active web page is written in Javascript. For the back-end, a Python server running Flask interfaces Bernoulli Naive Bayes models to classify tokens of text sent to it.

## Testing 
Tested the Extension on Amazon Website.
<p align="center">
    <img src="https://github.com/Nikita-silu/Cmos_dark_pattern/assets/123747415/5b3632f5-0bd9-4af3-882a-7d90847492ca" alt="logo" width=600 >
</p>
<p align="center">
    <img src="https://github.com/Nikita-silu/Cmos_dark_pattern/assets/123747415/55189e39-337e-4828-8659-c520dc273464" alt="logo" width=600 >
</p>
<p align="center">
    <img src="https://github.com/Nikita-silu/Cmos_dark_pattern/assets/123747415/e0399c51-fce8-4de4-a716-335807a6f093" alt="logo" width=600 >
</p>
<p align="center">
    <img src="https://github.com/Nikita-silu/Cmos_dark_pattern/assets/123747415/b0679103-1a4f-459f-b2bd-ebf233306f8d" alt="logo" width=600 >
</p>



## Reference
Dark Patterns at Scale: Findings from a Crawl of 11K Shopping Websites. Proceedings of the ACM on Human-Computer Interaction, 3(CSCW), 81.


