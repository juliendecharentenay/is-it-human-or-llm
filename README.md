# Is it human or llm?
This repository contains a proposal for self disclosure of usage of LLMs in short form articles, ie reading times between 3 and 10 minutes.

The disclosure works by displaying a badge in accordance with the definitions below at the __beginning__ of the article, such as 
under the article sub-title.

## Definitions
### Pure Human
![Pure Human](badges/pure_human.svg)

Works in this category are solely written by a human with no assistance from any LLM whatsoever. Tooling providing spelling, grammar correction, thesaurus are compliant. Non-compliant tooling would be any direct interaction with an LLM at any stage in the writing, including ideation stage, and indirect interaction through a writing editor tool, such as a paragraph completion.

### Human (mostly)
![Human (mostly)](badges/human_mostly.svg)

Works in this category are primarily written by a human. However the editing has benefited from assistance from LLM feedback, but not suggestions. The author is allowed to edit the work with consideration of the LLM feedback. The final piece remains fully written by a human, as the LLM input is limited to feedback only. Multiple rounds of feedback are acceptable.

### Assisted
![Assisted](badges/assisted.svg)

Works in this category are defined by a process whereby a complete work is produced by a human and then edited by an LLM. Whilst the ideation and the content is mostly human produced, an LLM is used in the editing process to iron out language, turn of phrase and clarity. The objective of the LLM editing is to maintain the same idea as the original work, but with an edited copy that has improved clarity.

### Inspired
![Inspired](badges/inspired.svg)

Works in this category are characterised by the use of an LLM in the ideation stage. An LLM is used before starting writing to develop and refine ideas used in the work, in collaboration with a human through prompting and the like. In this category, whilst the general topic is selected by the human, the angle, ideas, etc are developed through interaction with an LLM. These ideas are then taken on by the human writer to develop them into a suitable work that can then be polished (or not) by an LLM. Work in this category is a collaborative work between the human writer and the LLM.

### LLM (mostly)
![LLM (mostly)](badges/llm_mostly.svg)

Works in this category are characterised by the article being mostly written by an LLM. This may take the form of requesting an LLM to write a new article on a topic of choice, and prompting it in multiple steps or as a single shot to produce the final article. It can also be by preparing a set of bullet points corresponding to ideas to be expanded by the LLM; or even giving an example article and requesting a similar one to be re-written. In this category, most of the writing of the work can be attributed to the LLM. 

## How to use?

Below are some ways to incorporate these badges in your contribution.

### Raw HTML

The following snips ought to load the relevant badge, provide a link to this readme description and a brief description on mouse hover.

- Pure Human

```
<a href="https://github.com/juliendecharentenay/is-it-human-or-llm/tree/main?tab=readme-ov-file#pure-human" target="_blank">
  <img src="https://raw.githubusercontent.com/juliendecharentenay/is-it-human-or-llm/main/badges/pure_human.svg"
       alt="AI disclose: pure human"
       title="All writing done by a human with no AI/LLM contribution"
       />
</a>
```

- Human (mostly)

```
<a href="https://github.com/juliendecharentenay/is-it-human-or-llm/tree/main?tab=readme-ov-file#human-mostly" target="_blank">
  <img src="https://raw.githubusercontent.com/juliendecharentenay/is-it-human-or-llm/main/badges/human_mostly.svg"
       alt="AI disclose: Human (mostly)"
       title="All writing done by a human with feedback of AI/LLM considered"
       />
</a>
```

- Assisted

```
<a href="https://github.com/juliendecharentenay/is-it-human-or-llm/tree/main?tab=readme-ov-file#assisted" target="_blank">
  <img src="https://raw.githubusercontent.com/juliendecharentenay/is-it-human-or-llm/main/badges/assisted.svg"
       alt="AI disclose: Assisted"
       title="Writing done by a human with assistance of an AI/LLM in the editing stage"
       />
</a>
```

- Inspired

```
<a href="https://github.com/juliendecharentenay/is-it-human-or-llm/tree/main?tab=readme-ov-file#inspired" target="_blank">
  <img src="https://raw.githubusercontent.com/juliendecharentenay/is-it-human-or-llm/main/badges/inspired.svg"
       alt="AI disclose: Inspired"
       title="Human, AI/LLM collaboration to develop topic, with writing done by a human"
       />
</a>
```

- LLM (mostly)

```
<a href="https://github.com/juliendecharentenay/is-it-human-or-llm/tree/main?tab=readme-ov-file#llm-mostly" target="_blank">
  <img src="https://raw.githubusercontent.com/juliendecharentenay/is-it-human-or-llm/main/badges/llm_mostly.svg"
       alt="AI disclose: LLM (mostly)"
       title="Most of writing done by an AI/LLM under human supervision"
       />
</a>
```


