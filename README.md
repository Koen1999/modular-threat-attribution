# A Modular Approach to Cyber Threat Attribution using Opinion Pools

## Abstract
Cyber threat attribution can play an important role in increasing resilience against digital threats. Recent research focuses on automating the threat attribution process and on integrating it with other efforts, such as threat hunting. To support increasing automation of the cyber threat attribution process, this paper proposes a modular architecture as an alternative to current monolithic automated approaches. The modular architecture can utilize opinion pools to combine the output of concrete attributors. The proposed solution increases the tractability of the threat attribution problem and offers increased usability and interpretability, as opposed to monolithic alternatives. In addition, a Pairing Aggregator is proposed as an aggregation method that forms pairs of attributors based on distinct features to produce intermediary results before finally producing a single Probability Mass Function (PMF) as output. The Pairing Aggregator sequentially applies both the logarithmic opinion pool and the linear opinion pool. An experimental validation suggests that the modular approach does not result in decreased performance and can even enhance precision and recall compared to monolithic alternatives. The results also suggest that the Pairing Aggregator can improve precision over the linear and logarithmic opinion pools. Furthermore, the improved k-accuracy in the experiment suggests that forensic experts can leverage the resulting PMF during their manual attribution processes to enhance their efficiency.

## Citations
If you use the source code, the datasets, or otherwise draw from this work, please cite the following paper:

`Koen T. W. Teuwen, "A Modular Approach to Cyber Threat Attribution using Opinion Pools," Venue, City, country, Year, pp. ??-??, doi: ????????????????????.`

## License
This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
