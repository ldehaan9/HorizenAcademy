---
layout: post
type: article
title: "What is Consensus?"
description: "The Horizen Academy is a free educational platform on blockchain technology, cryptocurrency, and privacy. In this article, you learn about the consensus mechanism in a simple, understandable way."
permalink: /eli5/what-is-consensus/
topic: eli5
further_reads: [consensus_for_kids]
---

<table class="table lead">
    <tr>
        <td class="icon"><img src="/assets/post_files/eli5/what-is-consensus/Consensus.jpg" alt="Consensus"></td>
        <td>
            The <a href="{{ site.baseurl }}{% post_url /eli5/2000-01-01-what-is-a-blockchain %}">blockchain</a> records all the transfers of money. If you have only 1 ZEN, and create two transactions at the same time, attempting to spend the same coin twice, the network needs to agree on which of the two transactions was first, and therefore, is the valid one.
        </td>
    </tr>
</table> 

The consensus mechanism makes sure that the entire network agrees on the order of transactions. The network has to agree on the order of the most recent transactions before it can finalize a block. Once there is ageement, the block is released to the network and a new block is created.  This way nobody can cheat the system and spend more than they have.

There are different ways to come to a consensus in a [peer-to-peer network]({{ site.baseurl }}{% post_url /eli5/2000-01-06-what-is-a-peer-to-peer-network %}). On the Horizen blockchain, people vote with their computational power on the order of transactions. If your computer is twice as fast as mine then the chance of you deciding on the order of transactions is twice as high as me deciding on it.

