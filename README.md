# Fair Protocol's DataOS

<p align="justify">
<b>Note:</b> This project intends to be a module on top of the Fair Protocol project. For a better understanding of this document and this project as a whole, we recommend reading these documents in advance:
</p>

* [Fair Protocol Whitepaper](https://lqcpjipmt2d2daazjknargowboxuhn3wgealzbqdsjmwxbgli52q.arweave.net/XAT0oeyeh6GAGUqaCJnWC69Dt3YxALyGA5JZa4TLR3U);
* [DataOS original idea](https://q4xpz2buwrju4ai3gfzkfeu3vjn2rhb2crlw7epn77vzm6wg74cq.arweave.net/hy786DS0U04BGzFyopKbqluonDoUV2-R7f_rlnrG_wU);
* [ANS-108 standard](https://github.com/ArweaveTeam/arweave-standards/blob/ans-108/ans/ANS-108.md);
* [Rough Proposal about ANS-108 with DataOS](https://a3yl723e5dcuvz4eoign6eacpmglz3sbpq542i7477m3mrlp3pga.arweave.net/BvC_62ToxUrnhHIM3xACewy87kF8O80j_P_ZtkVv28w).

<p align="justify">
With this project, we intend to make two proposals for DataOS implementations using as a base the Fair Protocol. The first proposal would be similar to the "<a href="https://a3yl723e5dcuvz4eoign6eacpmglz3sbpq542i7477m3mrlp3pga.arweave.net/BvC_62ToxUrnhHIM3xACewy87kF8O80j_P_ZtkVv28w">Rough Proposal about ANS-108 with DataOS</a>" and would consist of creating an application to render data more efficiently. Our second proposal would be using inferred models in a decentralised way to create web pages.
</p>


# DataOS Information Renderer

<p align="justify">
This proposal would create a new application that would run on top of the Fair Protocol and perform three steps:
</p>

1. It would transform text prompts from users of this new application into GraphQL searches in Arweave;
1. It would interpret the results obtained in the first step and create an input in text prompt format; 
1. Use an Artificial Intelligence (AI) model in Fair Protocol to create a User Interface (UI) to display the obtained data optimally, passing through an API the input mentioned above.

<p align="justify">
Points 1 and 2 could be accomplished by the application using programming logic or AI models in the Fair Protocol, and the results of those services could be requested or obtained via an API.
</p>

<p align="justify">
Step 3 would use Renderers (from the <a href="https://a3yl723e5dcuvz4eoign6eacpmglz3sbpq542i7477m3mrlp3pga.arweave.net/BvC_62ToxUrnhHIM3xACewy87kF8O80j_P_ZtkVv28w">ANS-108 standard</a>) so that gateways would know that these transactions should have specific renderization rules.
</p>


# DataOS Web Pages Creator

<p align="justify">
This proposal would use a model from the Fair Protocol marketplace to generate and execute the code of a web page.
</p>

<p align="justify">
As this model could create several code errors, we would implement methods to make the application resilient. To achieve this, we can build the code using several different models, create programming logic to solve these problems, or even run AI models specialised in solving code problems.
</p>


# Next Steps

<p align="justify">
We will confirm the viability of these proposals, and depending on our research, we will implement them. Anyone from the Arweave community who would like to join or help with this idea, please get in touch.
</p>
