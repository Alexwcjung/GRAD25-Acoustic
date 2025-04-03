# ☘ Research Overview

This study aims to investigate whether Korean learners of English can accurately perceive and distinguish the vowels **/ʊ/**, **/u/**, and **/o/**, which represent subtle contrasts not present in the Korean vowel system. Since these distinctions do not exist in Korean, learners may fail to discriminate them at the perceptual level, which could lead to phonetic substitutions during production. By examining learners’ perceptual accuracy, the study seeks to determine whether perceptual difficulty is a key factor contributing to substitution errors in speech.

### Comparison of /ʊ/, /u/, and /o/ in English

| Feature             | /ʊ/                                          | /u/                                      | /o/ (typically /oʊ/)                     |
|---------------------|----------------------------------------------|-------------------------------------------|-------------------------------------------|
| **Vowel Type**      | Lax                                         | Tense                                    | Tense (often diphthongal)                 |
| **Height (F1)**     | High                                        | High                                     | Mid                                       |
| **Backness (F2)**   | Near-back                                   | Back                                     | Mid-back                                  |
| **Lip Rounding**    | Rounded                                     | Rounded                                  | Rounded                                   |
| **Length**          | Short                                       | Long                                     | Long (with glide /ʊ/ in diphthong)        |
| **Examples**        | *book*, *good*, *could*, *would*, *foot*    | *food*, *blue*, *boot*, *school*         | *go*, *boat*, *home*, *code*              |
| **Korean Equivalent**| No direct equivalent (between /ㅡ/ and /ㅜ/) | /ㅜ/ (as in *우*)                         | /ㅗ/ (as in *오*)                          |


## Research Questions

**RQ1.** To what extent do Korean learners accurately produce the English vowel **/ʊ/**, and how often is it substituted with [u] or [o]?

**RQ2.** How accurately can Korean learners perceptually identify the English vowel **/ʊ/**?

**RQ3.** Is there a statistically significant relationship between Korean learners’ perceptual accuracy of **/ʊ/** and their production accuracy of **/ʊ/**?


---
### 🐳 Step 1. Production Task

#### RQ1: To what extent do Korean learners accurately produce the English vowel **/ʊ/**, and how often is it substituted with **[u]** or **[o]**?

### 1.1. Task Procedure

#### ⚠️ Minimizing Experimental Awareness Effects

In speech experiments, participants’ awareness of the experimental focus can influence their performance.  
If learners are aware that their pronunciation of a specific sound is being evaluated, they may consciously monitor or exaggerate their articulation — a phenomenon known as the **task awareness effect** or **experimenter effect**. 

To avoid this bias, two key strategies were employed:

1. **The target vowel /ʊ/ was not disclosed to participants.**  
   The task was introduced as a general reading activity without any mention of vowel pronunciation. This ensured that learners’ speech remained natural and unmonitored.

2. **The production task was conducted before the perception task.**  
   Conducting the ABX perception task first may sensitize participants to subtle vowel differences, especially /ʊ/, /u/, and /o/. To avoid this potential priming effect, the production task was administered **before** the perception task.

---

#### 🎤 Recording Procedure

Participants were asked to read aloud 5–6 English sentences, each containing a word with the vowel **/ʊ/**.

Target words included: *book*, *foot*, *good*, *could*, *would*

> **Example sentence**:  
> *I would like to buy the book now.*

Each sentence was designed to place the target vowel in a natural sentence context.

### 1.2. Acoustic Analysis

All recordings were segmented and analyzed using **Praat**. The target vowel in each word was isolated, and its **F1** and **F2** values were measured at the temporal midpoint.

A reference vowel space was established using **native-speaker values**, against which learner productions were compared.

  | Vowel | F1 (Height) | F2 (Backness) | Notes                                |
  |-------|-------------|----------------|--------------------------------------|
  | /ʊ/   | Medium       | Medium–Low      | Short, lax vowel                     |
  | /u/   | Low          | Low             | Long, tense vowel                    |
  | /o/   | Medium       | Higher than /u/ | Often realized as a diphthong (/oʊ/) |



### 1.3. Statistical Analysis

#### A. Descriptive Statistics
> **Example**:  
>
>  | Realized Vowel | Frequency |
>  |----------------|-----------|
>  | [ʊ]            | 90       |
>  | [u]            | 160        |
>  | [o]            | 50        |

#### B. Inferential Statistics

##### (1) Chi-Square Test

**Purpose**  
A chi-square test will be conducted to determine whether the frequency distribution of vowel substitutions ([ʊ], [u], [o]) differs significantly from what would be expected by chance.
If a statistically significant difference is found (e.g., χ² = 15.3, p < .01), this would suggest that learners substitute [u] for /ʊ/ more frequently than expected, reflecting a systematic substitution pattern


##### (2) One-Way ANOVA (F1/F2 Analysis)

**Purpose**  
To test whether the **acoustic realizations** of [ʊ], [u], and [o] are significantly different in terms of **F1 and F2** values.

> **Example**:  

| Realized Vowel | Mean F1 (Hz) | Mean F2 (Hz) |
|----------------|--------------|--------------|
| **[ʊ]**         | 450          | 1100         |
| **[u]**         | 350          | 900          |
| **[o]**         | 500          | 1050         |


- **Dependent Variable**: F1 or F2
- **Independent Variable**: Realized vowel category ([ʊ], [u], [o])
- **Statistical Test**: One-way ANOVA


### 1.4. Summary: What Do Chi-Square and ANOVA Test?

Both **Chi-square** and **ANOVA** are inferential statistical tests that determine whether learners’ vowel substitutions are **statistically meaningful**, rather than due to chance.

| Analysis     | Research Question                             | Explanation                                                                 |
|--------------|------------------------------------------------|------------------------------------------------------------------------------|
| **Chi-square** | Which vowel is most frequently produced by learners? | → Tests whether the difference in production frequency is statistically significant (i.e., not due to chance) |
| **ANOVA**      | How do the learners' vowel productions differ acoustically? | → Tests whether the mean F1/F2 values of [ʊ], [u], and [o] differ significantly |

--------------
## 🐳 Step 2. Perception Task (ABX Test)

### RQ2: How accurately can Korean learners perceptually identify the English vowel **/ʊ/**?

### 2.1. Task Overview

Participants heard three audio stimuli in each trial: A, B, and X.  
- X matched either A or B in vowel quality (/ʊ/, /u/, /o/)  
- All three were different words  
- The task:  
  > **“Which one is X more similar to, A or B?”**

### 2.2. Stimulus Examples

| A–B Pair        | X Stimulus | Target Vowel | Correct Answer |
|-----------------|------------|---------------|----------------|
| *book* vs *boot* | *could*     | /ʊ/           | A              |
| *foot* vs *food* | *good*      | /ʊ/           | A              |
| *book* vs *boat* | *would*     | /ʊ/           | A              |
| *could* vs *coat*| *foot*      | /ʊ/           | A              |
| *blue* vs *good* | *boot*      | /u/           | A              |
| *would* vs *wrote*| *book*     | /ʊ/           | A              |

### 2.3. Experiment Design

| Element          | Details |
|------------------|---------|
| Total items      | 6–9 items (3 vowel pairs × 2–3 trials each) |
| Stimuli          | Native speaker recordings or TTS |
| Presentation     | A–B–X (randomized order, e.g., ABX or BAX) |
| Task             | “Which one is X more similar to, A or B?” |
| Scoring          | Accuracy (%) for /ʊ/-related trials only |

### 2.4. Statistical Analysis

**Goal**: To evaluate learners’ ability to accurately perceive the vowel /ʊ/.

#### A. Descriptive Statistics

The mean accuracy score for /ʊ/-related ABX trials will be calculated per participant.

#### B. Inferential Statistics

A repeated measures ANOVA may be conducted to examine overall differences in perception accuracy among the three vowel pairs (/ʊ/-/u/, /ʊ/-/o/, /u/-/o/).  
However, since the goal is to examine learners’ perception of **/ʊ/** specifically, only their accuracy on /ʊ/-related contrasts (e.g., /ʊ/-/u/, /ʊ/-/o/) will be averaged and used in the correlation analysis in Step 3.  
**Post-hoc comparisons will not be conducted**, as the specific pairwise differences are not the focus of this study.

> The average accuracy on /ʊ/-related ABX items will serve as each participant’s **perception score of /ʊ/**.

## 🐳Step 3. Perception–Production Correlation Analysis

### RQ3: Is there a statistically significant relationship between Korean learners’ perceptual accuracy of **/ʊ/** and their production accuracy of **/ʊ/**?

### 3.1. Variable Definition

| Variable | Description |
|----------|-------------|
| **X (Independent)**   | Perception accuracy of **/ʊ/** — calculated as the average correct responses on ABX trials where **/ʊ/** was the target vowel |
| **Y (Dependent)**     | Production accuracy of **/ʊ/** — percentage of correctly realized **[ʊ]** tokens when **/ʊ/** was the intended target in the reading task |


### 3.2. Statistical Analysis

**Correlation Analysis**

- **Pearson correlation coefficient (r)** will be used to examine the relationship between learners’ perceptual accuracy and production accuracy of **/ʊ/**.
- This test is appropriate if both variables are continuous and normally distributed.
- The analysis will determine whether there is a statistically significant linear association between the two skills (perception and production) for the target vowel.


### 3.3. Expected Results and Interpretation

| Result Scenario                  | Interpretation |
|----------------------------------|----------------|
| **Significant positive correlation**<br>(e.g., r > .5, p < .05) | Learners who perceive **/ʊ/** more accurately also tend to produce it more accurately.<br> → Suggests that perceptual ability may influence production accuracy. |
| **No significant correlation**   | Accurate perception of **/ʊ/** does not necessarily lead to accurate production.<br> → Production errors may arise from other factors (e.g., articulatory difficulty, L1 interference). |


> ✅ This step aims to determine whether accurate perception of /ʊ/ is a predictor of accurate production — supporting the theory that perception precedes production in second language acquisition.

