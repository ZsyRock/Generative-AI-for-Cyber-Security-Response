# Generative-AI-for-Cyber-Security-Response

### Summarize

I'm diving into a dataset packed with network nodes, links, and demands, aiming to build a [network topology](https://github.com/ZsyRock/Generative-AI-for-Cyber-Security-Response/blob/main/Generation-of-network-topologies/Generate-topology-from-data.png) and show the network topology dictionary that really nails down the connections between them. Along the way, I picked up a couple of key lessons:

- Getting that network topology out of raw data took way more time than I thought, especially with all the data preprocessing. Plus, every time I tried to add new data, it threw a wrench in the works. That got me thinking about using natural language processing (NLP) to handle network data more smoothly. Networks tend to follow certain patterns, so I'm betting that using AI-powered NLP could be a game-changer.
- I gave Generative Adversarial Networks (GANs) a shot to whip up network topologies straight from my dataset. But boy, did I underestimate the challenge! Still, I'm optimistic about what generative AI can bring to the table in the network world. I'm gonna keep digging into it and keep you posted on how it goes.

### the dataset is from:
@inproceedings{SNDlib10,
	author={S. Orlowski and M. Pi{\'o}ro and A. Tomaszewski and R. Wess{\"a}ly},
	booktitle={Proceedings of the 3rd International Network Optimization Conference (INOC 2007), Spa, Belgium},
	language={English},
	month={April},
	note={http://sndlib.zib.de, extended version accepted in Networks, 2009.},
	seealso={OrlowskiPioroTomaszewskiWessaely2009},
	title={{SNDlib} 1.0--{S}urvivable {N}etwork {D}esign {L}ibrary},
	year={2007},
	url={https://opus4.kobv.de/opus4-zib/frontdoor/deliver/index/docId/958/file/ZR-07-15.pdf}
}
(the link from original website seems expired, you can find the [dataset](https://sndlib.put.poznan.pl/home.action) here)
