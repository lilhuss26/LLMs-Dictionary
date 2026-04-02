# Header 

- **Last Updated** : 1/4/2026
- **Last Updater** : [lilhuss26](https://github.com/lilhuss26)
# Intro 
- **Purpose** : This file's goal Isn't collecting ALL models in one place, but quite the opposite, is kind of filtering. All mentioned models/providers will be latest OR actually used ones, that deserve mentioning. Making it a quick reference for any future projects.
- **To Mention** : [ArtificialAnalysis](https://artificialanalysis.ai), U can find more stats and comparison
# TOC 
- [**The Big Three**](#the-big-three)  
	- [Claude](#claude)  
	- [Gemini](#gemini)  
	- [OpenAI](#openai)  
- [**Families**](#families)  
	- [Mistral3](#Mistral3)  
	- [Inception](#Inception)
	- [Z.ai](#Z.ai)
	- [Qwen](#Qwen)
- [**Providers**](#providers)  
	- [OpenRouter](#open-router)  
	- [Groq](#groq)
# Legend
- **Pricing** in any table is *1M token input cost*/*1M token output cost*
- **Throughput** is tps (Tkens Per Second)
# The Big Three 
## [Claude](https://claude.com/pricing#api)
**Note** : Claude provides some older versions, with the same pricing, Except **Haiku** , Significantly cheaper, but with very low performance on the benchmarks.

| Name       | Cat    | Pricing | Tried? | ToolCalling | Throughput | Performance | Notes |
| ---------- | ------ | ------- | ------ | ----------- | ---------- | ----------- | ----- |
| Haiku 4.5  | Meduim | 1/5     | No     |             |            |             |       |
| Sonnet 4.6 | Large  | 3/15    | No     |             |            |             |       |
| Opus 4.6   | Super  | 5/25    | No     |             |            |             |       |

## OpenAI
| Name        | Cat   | Pricing | Tried? | ToolCalling | Throughput | Performance                         | Notes                                  |
| ----------- | ----- | ------- | ------ | ----------- | ---------- | ----------------------------------- | -------------------------------------- |
| Chat-GPT 4o | Large |         | Yes    | True        |            | Great, large prompt (deep analysis) |                                        |
| Chat-GPT 5  | Large |         | Yes    |             |            | Good                                | Slower, and it's output feels too soft |

---
# Families
## [Mistral3](https://mistral.ai/pricing#api)

| Name             | Cat    | Pricing | Tried? | ToolCalling | Throughput | Performance                               | Notes               |
| ---------------- | ------ | ------- | ------ | ----------- | ---------- | ----------------------------------------- | ------------------- |
| Mistral3-largest | Meduim | 0.5/1.5 | Yes    | True        | 30         | Great, Agent stable                       | SLOW                |
| Mistral3-24b     | Small  |         | No     | True        |            |                                           |                     |
| Mistral3-14b     | Small  | 0.2/0.2 | Yes    | True        | 98         | Agent stable, large prompts (Re-writting) | Small hullicantaion |
## [Inception](https://platform.inceptionlabs.ai)

| Name     | Cat    | Pricing   | Tried? | ToolCalling | Throughput | Performance                        | Notes |
| -------- | ------ | --------- | ------ | ----------- | ---------- | ---------------------------------- | ----- |
| Mercury2 | Meduim | 0.25/0.75 | Yes    | True        | 332        | Great, Agent very smart and stable |       |

---
# Providers 
## [OpenRouter](https://openrouter.ai)
**Note** : It's wide models coverage and big trial qouta, makes it the first option for exploration
 
| Models variaty | Free trial | Used | Notes                                                         |
| -------------- | ---------- | ---- | ------------------------------------------------------------- |
| All Models     | Enough     | Yes  | Free trial is random, stops at the same day OR Last for weeks |

## [Groq](https://console.groq.com/docs/models#get-all-available-models)

| Models variety   | Free trial | Yes | Notes |
| ---------------- | ---------- | --- | ----- |
| Small Collection | Enough     | No  |       |
