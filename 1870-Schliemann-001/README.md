# TroyDestroy (DUMMY EXAMPLE) 

*by Heinrich "Dummy" Schliemann* (NASSA submission :rocket:)

## License

**MIT**

## References

Homer. 1865. The Iliad of Homer. J. Murray (trad.).

## Further information

This module represents a Bronze Age siege and its destructive effect on a settlement. It takes the strength of two armies, one aggressor and another defender, and calculates the level of destruction of the defenders' city. The destructive effect over the defenders' city is proportional to the two contending strengths and a constant rate per unit of strength of the aggressor matched by the defender.

<a title="Unknown Corinthian pottery maker BCE, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Corinthian_aryballos_depicting_the_trojan_war_from_1887_jahrbuchdeskaiserich_1200x500.jpg"><img width="512" alt="Corinthian aryballos depicting the trojan war from 1887 jahrbuchdeskaiserich 1200x500" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Corinthian_aryballos_depicting_the_trojan_war_from_1887_jahrbuchdeskaiserich_1200x500.jpg/512px-Corinthian_aryballos_depicting_the_trojan_war_from_1887_jahrbuchdeskaiserich_1200x500.jpg"></a>

This model is a algorithm implemented in NetLogo and Python 3. Disclaimer: the code might require updates since it was written in the 19th century.

>"As I, Heinrich Schliemann, stood before the windswept ruins of Troy, I conceived of a method by which to render the great sieges of the Bronze Age not only in story, but in number. In my imagination, the clash of armies could be distilled into a model: the attackers bring forth their strength, the defenders theirs, and the destruction of the city is measured not in vague tales but in proportion to these opposing forces. I introduced a constant rate of devastation for every unit of aggressor strength that meets its match upon the walls, so that the outcome of a siege might be calculated, not merely told. In this way, the legendary sack of Troy, and indeed the fate of any ancient citadel, could be reenacted as a balance of strength, a numerical echo of what once transpired in blood and flame." (pseudo-Schliemann, 2025, *Siege Warfare: A Quantitative Approach to Ancient Battles*, p. 45, fictional citation by ChatGPT and Copilot)

Overview of the algorithm:

$$warEffect=-destructionRate*\frac{(attackerStrength)^2}{defenderStrength} $$

See full list of documentation resources in [`documentation`](documentation/tableOfContents.md).

### Acknowledgements

The "crossed swords" emoticon (⚔️) used as cover image was sourced at [Twitter Emoji (Twemoji) v14.0](https://github.com/twitter/twemoji) under CC BY 4.0.
