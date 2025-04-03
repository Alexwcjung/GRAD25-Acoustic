# Research Overview

This study aims to investigate whether Korean learners of English can accurately perceive and distinguish the vowels **/ʊ/**, **/u/**, and **/o/**, which represent subtle contrasts not present in the Korean vowel system. Since these distinctions do not exist in Korean, learners may fail to discriminate them at the perceptual level, which could lead to phonetic substitutions during production. By examining learners’ perceptual accuracy, the study seeks to determine whether perceptual difficulty is a key factor contributing to substitution errors in speech.

## Research Questions

**Q1.** To what extent is the English vowel **/ʊ/** substituted with **/u/** or **/o/** in the speech of Korean learners, and which substitution pattern is most frequent?

**Q2.** To what extent can Korean learners perceptually discriminate between the vowels **/ʊ/**, **/u/**, and **/o/** in English?

**Q3.** Is there a statistically significant relationship between Korean learners’ perceptual discrimination ability and their production accuracy of **/ʊ/**?

---

## Step 1. Production Task

### 1.1. Task Procedure

Participants were asked to read aloud 5–6 sentences containing target words with the vowel **/ʊ/**.  
Target words included: *book*, *foot*, *good*, *could*, *would*

> **Example sentence**:  
> *I would like to buy the book now.*

To avoid experimental awareness, participants were told this was a simple reading task.  
No mention of target vowels or the study's aim was given.

### 1.2. Acoustic Analysis

Each vowel token was segmented and analyzed in **Praat**.  
The formant values (**F1** and **F2**) were extracted at the temporal midpoint of each vowel.

| Vowel | F1 (Height) | F2 (Backness) | Notes |
|-------|-------------|----------------|-----------------------------|
| /ʊ/   | Medium       | Medium–Low      | Short, lax vowel            |
| /u/   | Low          | Low             | Long, tense vowel           |
| /o/   | Medium       | Higher than /u/ | Often realized as /oʊ/ glide |

### 1.3. Statistical Analysis

#### A. Descriptive Statistics

| Realized As | Frequency |
|-------------|-----------|
| **[ʊ]**      | 160       |
| **[u]**      | 90        |
| **[o]**      | 50        |

### 1.4. Why Use Both Chi-Square and ANOVA?

Both **Chi-square** and **ANOVA** are inferential statistical tests used to determine whether the observed substitution patterns are statistically significant — not due to chance.

| Analysis           | Research Question                                                               | Data Type              | Example                                                                 |
|--------------------|----------------------------------------------------------------------------------|-------------------------|-------------------------------------------------------------------------|
| **Chi-square test** | Which vowel ([ʊ], [u], [o]) is most frequently produced by learners?            | Categorical (frequency counts) | [ʊ]: 40 times, [u]: 60 times, [o]: 20 times → Is this difference statistically significant? |
| **ANOVA (F1/F2)**   | Are the acoustic characteristics (F1 and F2) of [ʊ], [u], and [o] significantly different? | Continuous (numeric values)   | Are the mean F1 or F2 values different across vowels → Statistically significant?          |

This dual approach provides insight into both the **frequency** and the **phonetic nature** of substitution errors.

---

#### B. Inferential Statistics

| Analysis         | Research Question                                             | Data Type         | Example                |
|------------------|----------------------------------------------------------------|--------------------|------------------------|
| **Chi-square test** | Which vowel is most frequently substituted for /ʊ/?            | Categorical (counts) | [ʊ]: 40, [u]: 60, [o]: 20 |
| **One-way ANOVA**   | Are the acoustic features (F1/F2) of [ʊ], [u], [o] significantly different? | Continuous (formant values) | Compare F1/F2 means |

##### (1) Chi-Square Test

- **H₀**: There is no significant difference in substitution frequency.
- **H₁**: Certain substitutions (e.g., [u], [o]) are more frequent than others.

**Interpretation Example**  
> Learners substituted [u] significantly more often than [ʊ] when attempting to pronounce /ʊ/.

---

##### (2) ANOVA (F1/F2)

- **DV**: F1 or F2  
- **IV**: Realized vowel category ([ʊ], [u], [o])  
- **Method**: One-way ANOVA

**Interpretation Example**  
> Based on F2 values, [ʊ] and [u] were significantly different, but [ʊ] and [o] were not.  
> → Learners may not acoustically distinguish [ʊ] from [o].

---

## Step 2. Perception Task (ABX Test)

### 2.1. Task Overview

Participants heard three audio stimuli in each trial: A, B, and X.  
- X matched either A or B in vowel quality (/ʊ/, /u/, /o/)  
- All three were different words  
- The task:  
  > **“Which one is X more similar to, A or B?”**

---

### 2.2. Stimulus Examples

| A–B Pair        | X Stimulus | Target Vowel | Correct Answer |
|-----------------|------------|---------------|----------------|
| *book* vs *boot* | *could*     | /ʊ/           | A              |
| *foot* vs *food* | *good*      | /ʊ/           | A              |
| *book* vs *boat* | *would*     | /ʊ/           | A              |
| *could* vs *coat*| *foot*      | /ʊ/           | A              |
| *blue* vs *good* | *boot*      | /u/           | A              |
| *would* vs *wrote*| *book*     | /ʊ/           | A              |

---

### 2.3. Experiment Design

| Element          | Details |
|------------------|---------|
| Total items      | 6–9 items (3 vowel pairs × 2–3 trials each) |
| Stimuli          | Native speaker recordings or TTS |
| Presentation     | A–B–X (randomized order, e.g., ABX or BAX) |
| Task             | “Which one is X more similar to, A or B?” |
| Scoring          | Accuracy (%) per vowel pair |

---

### 2.4. Statistical Analysis

**Goal**: Compare discrimination accuracy across vowel pairs.

#### Analysis Type: Repeated Measures ANOVA (RMA)

| Vowel Pair   | Accuracy (%) Example |
|--------------|----------------------|
| /ʊ/-/u/      | 66.7%                |
| /ʊ/-/o/      | 52.0%                |
| /u/-/o/      | 80.3%                |

#### Why use RMA?

| Condition                       | Satisfied? | Reason |
|--------------------------------|------------|--------|
| DV is continuous               | ✅         | Accuracy % |
| IV is categorical (3 vowel pairs) | ✅         | Within-subject factor |
| Same participant, multiple conditions | ✅         | Repeated design |

**Interpretation Example**  
> Participants performed significantly worse on /ʊ/-/o/ discrimination than on /ʊ/-/u/ and /u/-/o/.  
> → Suggests /ʊ/ and /o/ are the most confusable pair.

---

