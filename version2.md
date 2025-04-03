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
## 🐳 Step 1. Production Task

### RQ1: To what extent do Korean learners accurately produce the English vowel **/ʊ/**, and how often is it substituted with **[u]** or **[o]**?


### 1.1. Task Procedure

#### ⚠️ Minimizing Experimental Awareness Effects

In speech experiments, participants’ awareness of the experimental focus can influence their performance.  
If learners know their pronunciation is being evaluated, they may consciously monitor or exaggerate their articulation — a phenomenon known as the **task awareness effect** or **experimenter effect**.

To reduce this bias, two strategies were employed:

1. **The target vowel /ʊ/ was not disclosed** to participants.  
   The task was introduced as a general reading activity, with no mention of vowel pronunciation, ensuring more natural speech.

2. **The production task was conducted before the perception task** to avoid priming.  
   Conducting the ABX test first could sensitize participants to vowel contrasts (e.g., /ʊ/, /u/, /o/). Performing the production task first prevented such awareness from affecting pronunciation.

#### 🎤 Recording Procedure

Participants read aloud 5–6 English sentences, each containing a target word with the vowel **/ʊ/**.  
Target words included: *book*, *foot*, *good*, *could*, *would*

> **Example sentence**:  
> *I would like to buy the book now.*

Each sentence was designed to embed the vowel in a natural sentence context.


### 1.2. Acoustic Analysis

All recordings were segmented and analyzed using **Praat**.  
The target vowel in each token was isolated, and its **F1** and **F2** values were measured at the **temporal midpoint**, where the formant frequencies are most stable.

To assess vowel accuracy, a **reference vowel space** was established using native-speaker mean F1 and F2 values (e.g., Hillenbrand et al., 1995).  
Learners’ vowel realizations were compared to these reference values to evaluate phonetic deviation.

To determine whether these deviations were **statistically significant**, a **one-sample t-test** was conducted for each formant.  
This test compared the learners’ mean F1 and F2 values for /ʊ/ with the corresponding native-speaker norms.

This allowed us to assess not only whether the vowel was produced differently, but also whether the difference was meaningful in an inferential sense.


### 1.3. Statistical Analysis

#### A. Descriptive Statistics

The number of times each vowel was realized (i.e., perceived as [ʊ], [u], or [o]) was calculated:

| Realized Vowel | Frequency |
|----------------|-----------|
| [ʊ]            | 90        |
| [u]            | 160       |
| [o]            | 50        |

#### B. Inferential Statistics

##### (1) Chi-Square Test

**Purpose**  
To determine whether the frequency distribution of vowel substitutions ([ʊ], [u], [o]) differs significantly from what would be expected by chance.  
If a statistically significant result is obtained (e.g., χ² = 15.3, *p* < .01), it suggests a systematic substitution pattern (e.g., learners substituting [u] for /ʊ/ more frequently than expected).

##### (2) One-sample t-test (F1 and F2)

**Purpose**  
To examine whether learners’ mean F1 and F2 values for /ʊ/ significantly differ from native-speaker norms.  
This identifies whether the vowel is acoustically more open (F1↑), more back (F2↓), or both.

###### Example Table: One-sample t-test Results – Learner vs. Native F1/F2 (for /ʊ/)

| Measure | Native Mean (Hz) | Learner Mean (Hz) | SD (Learner) | t-value | df | p-value | Interpretation |
|---------|------------------|--------------------|--------------|---------|----|---------|----------------|
| **F1**  | 440              | 480                | 35           | 2.62    | 9  | .028     | Learners’ F1 is significantly higher → /ʊ/ is realized as a lower vowel |
| **F2**  | 1020             | 950                | 40           | -3.12   | 9  | .012     | Learners’ F2 is significantly lower → /ʊ/ is realized as a more back vowel |

###### Interpretation Notes

- **Higher F1** → The tongue is lower → The vowel is produced more like a **low vowel**
- **Lower F2** → The tongue is farther back → The vowel is produced more like a **back vowel**

📌 These results suggest that Korean learners tend to realize /ʊ/ with a more open and back articulation, making it acoustically closer to **/o/** or **/u/**.

### 1.4. Summary: What Do Chi-Square and One-sample t-test Tell Us?

| Analysis             | Research Focus                                      | Explanation |
|----------------------|------------------------------------------------------|-------------|
| **Chi-square**       | Which vowel is most frequently produced by learners? | → Tests whether substitution frequencies differ significantly from chance |
| **One-sample t-test**| How do learners' vowel realizations differ acoustically from native norms? | → Tests whether the mean F1 or F2 values of /ʊ/ differ significantly from native-speaker values |


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

#### B. Inferential Statistics : One-sample t-test – ABX Perception Accuracy vs. Chance Level (50%)
### Example Table

| Vowel Pair   | Mean Accuracy (%) | t-value | df | p-value | Interpretation                                |
|--------------|--------------------|---------|----|---------|-----------------------------------------------|
| /ʊ/-/u/      | 68.2               | 4.35    | 19 | .0003   | Significantly above chance → discrimination successful |
| /ʊ/-/o/      | 55.6               | 1.89    | 19 | .075    | Not significantly different from chance → possible confusion |


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

