# 🎯 GUARANTEED 60+ MARKS STRATEGY

## **Complete Focused Study Material**

---

# **UNIT-V: HYPOTHESIS TESTING (20 Marks)**

---

## **1️⃣ Z-TEST FOR SINGLE MEAN**

### **Formula:**

$$Z = \frac{\bar{x} - \mu}{\frac{\sigma}{\sqrt{n}}}$$

**When to use:**
- Sample size **n ≥ 30**
- Testing claim about **one population mean**

---

### **Standard Steps:**

**Step 1:** Write H₀ and H₁

**Step 2:** Note given data (n, x̄, σ, μ, α)

**Step 3:** Calculate Z

**Step 4:** Find critical value from table

**Step 5:** Compare and decide

**Step 6:** Write conclusion

---

### **PROBLEM - Type 1: Two-tailed test**

**Question:**

A company claims average bulb life is 1200 hours. Sample of 50 bulbs: mean = 1180 hours, S.D = 100 hours. Test at 5% level.

---

**SOLUTION:**

**Step 1: Hypotheses**

H₀: μ = 1200 (claim is true)

H₁: μ ≠ 1200 (claim is false) - **Two-tailed**

---

**Step 2: Given**
- n = 50
- x̄ = 1180
- σ = 100
- μ = 1200
- α = 0.05

---

**Step 3: Calculate Z**

$$Z = \frac{1180 - 1200}{\frac{100}{\sqrt{50}}}$$

$$= \frac{-20}{\frac{100}{7.071}}$$

$$= \frac{-20}{14.14}$$

$$= -1.414$$

**|Z| = 1.414**

---

**Step 4: Critical value**

Two-tailed at 5%: **Z₀.₀₅ = ±1.96**

---

**Step 5: Decision**

|Z| = 1.414 < 1.96

**Accept H₀**

---

**Step 6: Conclusion**

At 5% level, company's claim is **VALID**.

---

### **PROBLEM - Type 2: One-tailed test**

**Question:**

A principal claims students score at least 70 on average. Sample of 100 students: mean = 68, S.D = 15. Test at 5% level.

---

**SOLUTION:**

**Hypotheses:**

H₀: μ = 70

H₁: μ < 70 (**left-tailed** - testing "at least")

**Given:** n=100, x̄=68, σ=15, μ=70, α=0.05

**Calculate:**

$$Z = \frac{68 - 70}{\frac{15}{\sqrt{100}}} = \frac{-2}{1.5} = -1.333$$

**Critical value:** Z₀.₀₅ = -1.645 (left-tailed)

**Decision:** |Z| = 1.333 < 1.645 → **Accept H₀**

**Conclusion:** Claim is valid at 5% level.

---

### **Key Points to Remember:**

✅ **Two-tailed:** H₁ uses ≠ (claim says "equal to")

✅ **Right-tailed:** H₁ uses > (claim says "at most")

✅ **Left-tailed:** H₁ uses < (claim says "at least")

✅ **Critical values:**
- 5% two-tailed: ±1.96
- 5% one-tailed: ±1.645
- 1% two-tailed: ±2.58
- 1% one-tailed: ±2.33

---

## **2️⃣ Z-TEST FOR DIFFERENCE OF MEANS**

### **Formula:**

$$Z = \frac{\bar{x}_1 - \bar{x}_2}{\sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma_2^2}{n_2}}}$$

**When to use:**
- **Two samples**, both **n ≥ 30**
- Comparing **two population means**

---

### **PROBLEM - Standard Type**

**Question:**

Sample 1: n₁=100, x̄₁=65, σ₁=8

Sample 2: n₂=80, x̄₂=60, σ₂=7

Test if means differ significantly at 5% level.

---

**SOLUTION:**

**Step 1: Hypotheses**

H₀: μ₁ = μ₂ (no difference)

H₁: μ₁ ≠ μ₂ (difference exists) - Two-tailed

---

**Step 2: Given**
- Sample 1: n₁=100, x̄₁=65, σ₁=8
- Sample 2: n₂=80, x̄₂=60, σ₂=7
- α = 0.05

---

**Step 3: Calculate Z**

$$Z = \frac{65 - 60}{\sqrt{\frac{64}{100} + \frac{49}{80}}}$$

$$= \frac{5}{\sqrt{0.64 + 0.6125}}$$

$$= \frac{5}{\sqrt{1.2525}}$$

$$= \frac{5}{1.119}$$

$$= 4.468$$

---

**Step 4: Critical value**

Two-tailed at 5%: **Z₀.₀₅ = ±1.96**

---

**Step 5: Decision**

|Z| = 4.468 > 1.96

**Reject H₀**

---

**Step 6: Conclusion**

Means differ **significantly** at 5% level.

---

### **PROBLEM - Word Problem**

**Question:**

Boys (n=120): mean score = 72, S.D = 12

Girls (n=100): mean score = 70, S.D = 10

Test at 1% level if there's significant difference.

---

**SOLUTION:**

**Hypotheses:** H₀: μ₁ = μ₂, H₁: μ₁ ≠ μ₂

**Calculate:**

$$Z = \frac{72 - 70}{\sqrt{\frac{144}{120} + \frac{100}{100}}}$$

$$= \frac{2}{\sqrt{1.2 + 1}} = \frac{2}{\sqrt{2.2}} = \frac{2}{1.483} = 1.349$$

**Critical value:** Z₀.₀₁ = ±2.58

**Decision:** 1.349 < 2.58 → **Accept H₀**

**Conclusion:** No significant difference at 1% level.

---

### **Quick Calculation Tip:**

$$\text{Denominator} = \sqrt{\frac{\sigma_1^2}{n_1} + \frac{\sigma_2^2}{n_2}}$$

Calculate each fraction separately, add, then take square root!

---

## **3️⃣ t-TEST FOR DIFFERENCE OF MEANS (Small Sample)**

### **Formula:**

$$t = \frac{\bar{x}_1 - \bar{x}_2}{s\sqrt{\frac{1}{n_1} + \frac{1}{n_2}}}$$

**Pooled Standard Deviation:**

$$s^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1 + n_2 - 2}$$

**Degrees of freedom:** ν = n₁ + n₂ - 2

**When to use:**
- **Both samples small** (n < 30)
- Comparing two means

---

### **PROBLEM - Complete Solution**

**Question:**

Sample 1: n₁=8, x̄₁=12, s₁=2

Sample 2: n₂=10, x̄₂=10, s₂=1.5

Test if means differ at 5% level.

---

**SOLUTION:**

**Step 1: Hypotheses**

H₀: μ₁ = μ₂

H₁: μ₁ ≠ μ₂

---

**Step 2: Given**
- n₁=8, x̄₁=12, s₁=2
- n₂=10, x̄₂=10, s₂=1.5
- α = 0.05

---

**Step 3: Calculate pooled variance**

$$s^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1+n_2-2}$$

$$= \frac{(8-1)(2)^2 + (10-1)(1.5)^2}{8+10-2}$$

$$= \frac{7 \times 4 + 9 \times 2.25}{16}$$

$$= \frac{28 + 20.25}{16}$$

$$= \frac{48.25}{16} = 3.016$$

$$s = \sqrt{3.016} = 1.737$$

---

**Step 4: Calculate t**

$$t = \frac{12 - 10}{1.737\sqrt{\frac{1}{8} + \frac{1}{10}}}$$

$$= \frac{2}{1.737\sqrt{0.125 + 0.10}}$$

$$= \frac{2}{1.737\sqrt{0.225}}$$

$$= \frac{2}{1.737 \times 0.474}$$

$$= \frac{2}{0.823}$$

$$= 2.431$$

---

**Step 5: Degrees of freedom**

ν = n₁ + n₂ - 2 = 8 + 10 - 2 = **16**

---

**Step 6: Critical value**

From t-table: **t₀.₀₅(16) = 2.120** (two-tailed)

---

**Step 7: Decision**

|t| = 2.431 > 2.120

**Reject H₀**

---

**Step 8: Conclusion**

Means differ **significantly** at 5% level.

---

### **PROBLEM - Another Example**

**Question:**

Sample 1: n₁=12, x̄₁=85, s₁=5

Sample 2: n₂=15, x̄₂=82, s₂=6

Test at 5% level.

---

**SOLUTION:**

**Step 1: Pooled variance**

$$s^2 = \frac{11(25) + 14(36)}{25} = \frac{275 + 504}{25} = \frac{779}{25} = 31.16$$

$$s = 5.582$$

---

**Step 2: Calculate t**

$$t = \frac{85-82}{5.582\sqrt{\frac{1}{12}+\frac{1}{15}}}$$

$$= \frac{3}{5.582\sqrt{0.0833+0.0667}}$$

$$= \frac{3}{5.582 \times 0.387} = \frac{3}{2.160} = 1.389$$

---

**Step 3: Decision**

ν = 25, t₀.₀₅(25) = 2.060

|t| = 1.389 < 2.060 → **Accept H₀**

**Conclusion:** No significant difference.

---

### **Important t-table Values (Memorize these):**

| d.f. (ν) | 5% (two-tailed) | 1% (two-tailed) |
|---------|-----------------|-----------------|
| 5 | 2.571 | 4.032 |
| 10 | 2.228 | 3.169 |
| 15 | 2.131 | 2.947 |
| 20 | 2.086 | 2.845 |
| 25 | 2.060 | 2.787 |
| 30 | 2.042 | 2.750 |

---

### **Step-by-Step Checklist:**

**For t-test difference of means:**

☑️ Step 1: Find pooled variance s²

☑️ Step 2: Find pooled S.D (s)

☑️ Step 3: Calculate t statistic

☑️ Step 4: Find d.f. = n₁+n₂-2

☑️ Step 5: Get critical value from table

☑️ Step 6: Compare and decide

---

---

# **UNIT-II: BINOMIAL & POISSON (15 Marks)**

---

## **4️⃣ BINOMIAL DISTRIBUTION**

### **Formula:**

$$P(X = r) = \binom{n}{r} p^r q^{n-r}$$

where:
- n = number of trials
- r = number of successes
- p = probability of success
- q = 1 - p
- $$\binom{n}{r} = \frac{n!}{r!(n-r)!}$$

---

### **Mean & Variance:**

$$\text{Mean} = np$$

$$\text{Variance} = npq$$

---

### **PROBLEM - Type 1: Basic Probability**

**Question:**

A coin is tossed 6 times. Find probability of:

(a) Exactly 4 heads

(b) At least 4 heads

(c) At most 2 heads

---

**SOLUTION:**

**Given:**
- n = 6
- p = 1/2 (probability of head)
- q = 1/2
- X ~ B(6, 1/2)

---

**(a) P(X = 4)**

$$P(X=4) = \binom{6}{4} \left(\frac{1}{2}\right)^4 \left(\frac{1}{2}\right)^2$$

$$= \binom{6}{4} \left(\frac{1}{2}\right)^6$$

$$\binom{6}{4} = \frac{6!}{4!2!} = \frac{6 \times 5}{2} = 15$$

$$P(X=4) = 15 \times \frac{1}{64} = \frac{15}{64} = 0.234$$

---

**(b) P(X ≥ 4) = At least 4**

$$P(X \geq 4) = P(4) + P(5) + P(6)$$

$$P(5) = \binom{6}{5} \left(\frac{1}{2}\right)^6 = 6 \times \frac{1}{64} = \frac{6}{64}$$

$$P(6) = \binom{6}{6} \left(\frac{1}{2}\right)^6 = 1 \times \frac{1}{64} = \frac{1}{64}$$

$$P(X \geq 4) = \frac{15+6+1}{64} = \frac{22}{64} = 0.344$$

---

**(c) P(X ≤ 2) = At most 2**

$$P(X \leq 2) = P(0) + P(1) + P(2)$$

$$P(0) = \frac{1}{64}, \quad P(1) = \frac{6}{64}, \quad P(2) = \frac{15}{64}$$

$$P(X \leq 2) = \frac{1+6+15}{64} = \frac{22}{64} = 0.344$$

---

### **PROBLEM - Type 2: Given Mean & Variance, Find n and p**

**Question:**

In a binomial distribution, mean = 6 and variance = 4.

Find: (a) n and p (b) P(X = 0)

---

**SOLUTION:**

**Given:**
- Mean = np = 6
- Variance = npq = 4

---

**(a) Find n and p**

**Step 1: Divide**

$$\frac{\text{Variance}}{\text{Mean}} = \frac{npq}{np} = q$$

$$q = \frac{4}{6} = \frac{2}{3}$$

---

**Step 2: Find p**

$$p = 1 - q = 1 - \frac{2}{3} = \frac{1}{3}$$

---

**Step 3: Find n**

$$np = 6$$

$$n \times \frac{1}{3} = 6$$

$$n = 18$$

---

**Answer:** n = 18, p = 1/3, q = 2/3

---

**(b) Find P(X = 0)**

$$P(X=0) = \binom{18}{0} \left(\frac{1}{3}\right)^0 \left(\frac{2}{3}\right)^{18}$$

$$= \left(\frac{2}{3}\right)^{18}$$

$$= (0.667)^{18}$$

$$= 0.000577$$

---

### **PROBLEM - Type 3: Defective Items**

**Question:**

5% items are defective. If 20 items are selected, find:

(a) Exactly 2 defective

(b) At most 2 defective

(c) At least 1 defective

---

**SOLUTION:**

**Given:**
- n = 20
- p = 0.05
- q = 0.95

---

**(a) P(X = 2)**

$$P(X=2) = \binom{20}{2} (0.05)^2 (0.95)^{18}$$

$$\binom{20}{2} = \frac{20 \times 19}{2} = 190$$

$$P(X=2) = 190 \times 0.0025 \times 0.3972$$

$$= 0.189$$

---

**(b) P(X ≤ 2)**

$$P(X \leq 2) = P(0) + P(1) + P(2)$$

$$P(0) = (0.95)^{20} = 0.3585$$

$$P(1) = 20 \times 0.05 \times (0.95)^{19} = 0.3774$$

$$P(2) = 0.189$$

$$P(X \leq 2) = 0.3585 + 0.3774 + 0.189 = 0.925$$

---

**(c) P(X ≥ 1)**

**Using complement (shortcut!):**

$$P(X \geq 1) = 1 - P(X=0)$$

$$= 1 - 0.3585 = 0.642$$

---

### **Quick Tips:**

✅ **"At least k"** = 1 - (sum from 0 to k-1)

✅ **"At most k"** = sum from 0 to k

✅ **For p = 0.5:** Calculations become simpler

✅ **Mean/Variance** trick: q = Var/Mean, then find p and n

---

## **5️⃣ POISSON DISTRIBUTION**

### **Formula:**

$$P(X = r) = \frac{e^{-\lambda} \lambda^r}{r!}$$

where λ = average number of occurrences

---

### **Mean & Variance:**

$$\text{Mean} = \lambda$$

$$\text{Variance} = \lambda$$

**Key property:** Mean = Variance

---

### **Important e^(-λ) Values:**

| λ | e^(-λ) |
|---|--------|
| 1 | 0.3679 |
| 2 | 0.1353 |
| 3 | 0.0498 |
| 4 | 0.0183 |
| 5 | 0.0067 |

---

### **PROBLEM - Type 1: Given λ**

**Question:**

If X follows Poisson distribution with λ = 2, find:

(a) P(X = 0)

(b) P(X = 3)

(c) P(X ≤ 2)

(d) P(X ≥ 1)

---

**SOLUTION:**

**Given:** λ = 2, e^(-2) = 0.1353

---

**(a) P(X = 0)**

$$P(X=0) = \frac{e^{-2} \times 2^0}{0!} = e^{-2} = 0.1353$$

---

**(b) P(X = 3)**

$$P(X=3) = \frac{e^{-2} \times 2^3}{3!}$$

$$= \frac{0.1353 \times 8}{6}$$

$$= \frac{1.0824}{6} = 0.1804$$

---

**(c) P(X ≤ 2)**

$$P(X \leq 2) = P(0) + P(1) + P(2)$$

$$P(1) = \frac{0.1353 \times 2}{1} = 0.2706$$

$$P(2) = \frac{0.1353 \times 4}{2} = 0.2706$$

$$P(X \leq 2) = 0.1353 + 0.2706 + 0.2706 = 0.6765$$

---

**(d) P(X ≥ 1)**

**Using complement:**

$$P(X \geq 1) = 1 - P(0) = 1 - 0.1353 = 0.8647$$

---

### **PROBLEM - Type 2: Given Mean**

**Question:**

Phone calls arrive at rate of 5 per hour (Poisson). Find:

(a) Probability of exactly 4 calls

(b) At most 2 calls

(c) Variance

---

**SOLUTION:**

**Given:** Mean = λ = 5, e^(-5) = 0.00674

---

**(a) P(X = 4)**

$$P(X=4) = \frac{e^{-5} \times 5^4}{4!}$$

$$= \frac{0.00674 \times 625}{24}$$

$$= \frac{4.2125}{24} = 0.1755$$

---

**(b) P(X ≤ 2)**

$$P(0) = 0.00674$$

$$P(1) = 0.00674 \times 5 = 0.0337$$

$$P(2) = \frac{0.00674 \times 25}{2} = 0.0842$$

$$P(X \leq 2) = 0.00674 + 0.0337 + 0.0842 = 0.125$$

---

**(c) Variance**

For Poisson: **Variance = λ = 5**

---

### **PROBLEM - Type 3: Accidents/Errors**

**Question:**

Average 3 accidents per week. Find probability of:

(a) No accident in a week

(b) At least 2 accidents

(c) Between 2 and 4 (inclusive)

---

**SOLUTION:**

**Given:** λ = 3, e^(-3) = 0.0498

---

**(a) P(X = 0)**

$$P(0) = e^{-3} = 0.0498$$

---

**(b) P(X ≥ 2)**

$$P(X \geq 2) = 1 - [P(0) + P(1)]$$

$$P(1) = 0.0498 \times 3 = 0.1494$$

$$P(X \geq 2) = 1 - (0.0498 + 0.1494) = 0.8008$$

---

**(c) P(2 ≤ X ≤ 4)**

$$P(2) = \frac{0.0498 \times 9}{2} = 0.2241$$

$$P(3) = \frac{0.0498 \times 27}{6} = 0.2241$$

$$P(4) = \frac{0.0498 \times 81}{24} = 0.1680$$

$$P(2 \leq X \leq 4) = 0.2241 + 0.2241 + 0.1680 = 0.616$$

---

### **Poisson Approximation to Binomial**

**When:**
- n is large (n ≥ 20)
- p is small (p ≤ 0.05)
- Use λ = np

**Example:**

n = 100, p = 0.02

Use Poisson with λ = 100 × 0.02 = 2

Then calculate using Poisson formula!

---

---

# **UNIT-IV: CORRELATION & REGRESSION (15 Marks)**

---

## **6️⃣ CORRELATION COEFFICIENT**

### **Formula:**

$$r = \frac{n\sum xy - (\sum x)(\sum y)}{\sqrt{[n\sum x^2 - (\sum x)^2][n\sum y^2 - (\sum y)^2]}}$$

**Properties:**
- -1 ≤ r ≤ +1
- r = +1: Perfect positive correlation
- r = -1: Perfect negative correlation
- r = 0: No correlation

---

### **PROBLEM - Standard Type**

**Question:**

Calculate correlation coefficient:

| x | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| y | 2 | 5 | 3 | 8 | 7 |

---

**SOLUTION:**

**Step 1: Calculation table**

| x | y | xy | x² | y² |
|---|---|----|----|-----|
| 1 | 2 | 2 | 1 | 4 |
| 2 | 5 | 10 | 4 | 25 |
| 3 | 3 | 9 | 9 | 9 |
| 4 | 8 | 32 | 16 | 64 |
| 5 | 7 | 35 | 25 | 49 |
| **Σ** | **25** | **88** | **55** | **151** |

**Totals:**
- n = 5
- Σx = 15
- Σy = 25
- Σxy = 88
- Σx² = 55
- Σy² = 151

---

**Step 2: Calculate numerator**

$$\text{Numerator} = n\sum xy - (\sum x)(\sum y)$$

$$= 5(88) - (15)(25)$$

$$= 440 - 375 = 65$$

---

**Step 3: Calculate denominator - Part 1**

$$n\sum x^2 - (\sum x)^2 = 5(55) - (15)^2$$

$$= 275 - 225 = 50$$

---

**Step 4: Calculate denominator - Part 2**

$$n\sum y^2 - (\sum y)^2 = 5(151) - (25)^2$$

$$= 755 - 625 = 130$$

---

**Step 5: Calculate denominator**

$$\text{Denominator} = \sqrt{50 \times 130} = \sqrt{6500} = 80.62$$

---

**Step 6: Calculate r**

$$r = \frac{65}{80.62} = 0.806$$

---

**ANSWER:** r = 0.806 (Strong positive correlation)

---

### **PROBLEM - Another Example**

**Question:**

| X | 10 | 12 | 13 | 16 | 17 | 20 |
|---|---|---|---|---|---|---|
| Y | 18 | 20 | 22 | 27 | 21 | 30 |

Find correlation coefficient.

---

**SOLUTION:**

**Calculation Table:**

| X | Y | XY | X² | Y² |
|---|---|----|----|-----|
| 10 | 18 | 180 | 100 | 324 |
| 12 | 20 | 240 | 144 | 400 |
| 13 | 22 | 286 | 169 | 484 |
| 16 | 27 | 432 | 256 | 729 |
| 17 | 21 | 357 | 289 | 441 |
| 20 | 30 | 600 | 400 | 900 |
| **Σ** | **138** | **2095** | **1358** | **3278** |

- n = 6
- ΣX = 88
- ΣY = 138

---

**Numerator:**

$$6(2095) - (88)(138) = 12570 - 12144 = 426$$

---

**Denominator:**

$$\sqrt{[6(1358) - 88^2][6(3278) - 138^2]}$$

$$= \sqrt{[8148-7744][19668-19044]}$$

$$= \sqrt{404 \times 624} = \sqrt{252096} = 502.09$$

---

**r:**

$$r = \frac{426}{502.09} = 0.848$$

**ANSWER:** r = 0.848 (Very strong positive correlation)

---

## **7️⃣ REGRESSION LINES (BOTH)**

### **Formulas:**

**Regression coefficient of Y on X:**

$$b_{yx} = \frac{n\sum xy - (\sum x)(\sum y)}{n\sum x^2 - (\sum x)^2}$$

**Regression coefficient of X on Y:**

$$b_{xy} = \frac{n\sum xy - (\sum x)(\sum y)}{n\sum y^2 - (\sum y)^2}$$

---

**Regression Lines:**

**Y on X:** $$Y - \bar{y} = b_{yx}(X - \bar{x})$$

**X on Y:** $$X - \bar{x} = b_{xy}(Y - \bar{y})$$

---

**Relationship:**

$$r = \sqrt{b_{yx} \times b_{xy}}$$ (take sign of b's)

---

### **PROBLEM - Complete Solution**

**Question:**

Find both regression lines and r:

| x | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| y | 2 | 5 | 3 | 8 | 7 |

---

**SOLUTION:**

**Use previous calculations:**
- n = 5
- Σx = 15, Σy = 25
- Σxy = 88
- Σx² = 55, Σy² = 151

---

**Step 1: Find means**

$$\bar{x} = \frac{15}{5} = 3$$

$$\bar{y} = \frac{25}{5} = 5$$

---

**Step 2: Find b_yx (Y on X)**

$$b_{yx} = \frac{5(88) - (15)(25)}{5(55) - (15)^2}$$

$$= \frac{440 - 375}{275 - 225}$$

$$= \frac{65}{50} = 1.3$$

---

**Step 3: Regression line of Y on X**

$$Y - 5 = 1.3(X - 3)$$

$$Y - 5 = 1.3X - 3.9$$

$$Y = 1.3X + 1.1$$

---

**Step 4: Find b_xy (X on Y)**

$$b_{xy} = \frac{5(88) - (15)(25)}{5(151) - (25)^2}$$

$$= \frac{65}{755 - 625}$$

$$= \frac{65}{130} = 0.5$$

---

**Step 5: Regression line of X on Y**

$$X - 3 = 0.5(Y - 5)$$

$$X - 3 = 0.5Y - 2.5$$

$$X = 0.5Y + 0.5$$

---

**Step 6: Find r**

$$r = \sqrt{b_{yx} \times b_{xy}}$$

$$= \sqrt{1.3 \times 0.5} = \sqrt{0.65} = 0.806$$

(Positive since both b's are positive)

---

**ANSWER:**

**Y on X:** Y = 1.3X + 1.1

**X on Y:** X = 0.5Y + 0.5

**r = 0.806**

---

### **PROBLEM - With Prediction**

**Question:**

| X | 65 | 66 | 67 | 67 | 68 | 69 | 70 | 72 |
|---|---|---|---|---|---|---|---|---|
| Y | 67 | 68 | 65 | 68 | 72 | 72 | 69 | 71 |

Find: (a) Regression line of Y on X

(b) Estimate Y when X = 68

---

**SOLUTION:**

**Quick Calculations:**
- n = 8
- ΣX = 544, ΣY = 552
- ΣXY = 37560
- ΣX² = 37028, ΣY² = 38132

---

**Step 1: Means**

$$\bar{X} = \frac{544}{8} = 68$$

$$\bar{Y} = \frac{552}{8} = 69$$

---

**Step 2: b_yx**

$$b_{yx} = \frac{8(37560) - (544)(552)}{8(37028) - (544)^2}$$

$$= \frac{300480 - 300288}{296224 - 295936}$$

$$= \frac{192}{288} = 0.667$$

---

**Step 3: Regression equation**

$$Y - 69 = 0.667(X - 68)$$

$$Y = 0.667X + 23.64$$

---

**Step 4: Estimate for X = 68**

$$Y = 0.667(68) + 23.64 = 69$$

---

**ANSWER:**

**(a)** Y = 0.667X + 23.64

**(b)** Y = 69 when X = 68

---

## **8️⃣ STRAIGHT LINE FITTING**

### **Formula:**

Fit: **y = a + bx**

$$b = \frac{n\sum xy - \sum x \sum y}{n\sum x^2 - (\sum x)^2}$$

$$a = \frac{\sum y - b\sum x}{n}$$

---

### **PROBLEM - Standard Type**

**Question:**

Fit straight line y = a + bx:

| x | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| y | 3 | 7 | 9 | 13 | 15 |

---

**SOLUTION:**

**Step 1: Calculation table**

| x | y | xy | x² |
|---|---|----|----|
| 1 | 3 | 3 | 1 |
| 2 | 7 | 14 | 4 |
| 3 | 9 | 27 | 9 |
| 4 | 13 | 52 | 16 |
| 5 | 15 | 75 | 25 |
| **Σ** | **47** | **171** | **55** |

**Totals:**
- n = 5
- Σx = 15
- Σy = 47
- Σxy = 171
- Σx² = 55

---

**Step 2: Calculate b**

$$b = \frac{5(171) - (15)(47)}{5(55) - (15)^2}$$

$$= \frac{855 - 705}{275 - 225}$$

$$= \frac{150}{50} = 3$$

---

**Step 3: Calculate a**

$$a = \frac{47 - 3(15)}{5}$$

$$= \frac{47 - 45}{5}$$

$$= \frac{2}{5} = 0.4$$

---

**ANSWER:**

**Fitted line:** y = 0.4 + 3x

---

### **PROBLEM - With Estimation**

**Question:**

Fit y = a + bx:

| x | 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|---|
| y | 1 | 1.8 | 3.3 | 4.5 | 6.3 |

Estimate y when x = 2.5

---

**SOLUTION:**

**Calculation Table:**

| x | y | xy | x² |
|---|---|----|----|
| 0 | 1.0 | 0.0 | 0 |
| 1 | 1.8 | 1.8 | 1 |
| 2 | 3.3 | 6.6 | 4 |
| 3 | 4.5 | 13.5 | 9 |
| 4 | 6.3 | 25.2 | 16 |
| **Σ** | **16.9** | **47.1** | **30** |

- n = 5, Σx = 10

---

**Calculate b:**

$$b = \frac{5(47.1) - (10)(16.9)}{5(30) - 100}$$

$$= \frac{235.5 - 169}{150 - 100} = \frac{66.5}{50} = 1.33$$

---

**Calculate a:**

$$a = \frac{16.9 - 1.33(10)}{5} = \frac{16.9 - 13.3}{5} = 0.72$$

---

**Fitted line:** y = 0.72 + 1.33x

---

**Estimate for x = 2.5:**

$$y = 0.72 + 1.33(2.5) = 0.72 + 3.325 = 4.045$$

---

**ANSWER:**

**Line:** y = 0.72 + 1.33x

**When x = 2.5, y = 4.05**

---

---

# **UNIT-III: NORMAL DISTRIBUTION (10 Marks)**

---

## **9️⃣ NORMAL DISTRIBUTION**

### **Standardization Formula:**

$$Z = \frac{X - \mu}{\sigma}$$

where:
- X = value
- μ = mean
- σ = standard deviation
- Z = standard normal variable

**Then use Z-table to find P(Z ≤ z)**

---

### **Properties:**

**Symmetry:**

$$P(Z < -z) = 1 - P(Z < z)$$

$$P(a < Z < b) = P(Z < b) - P(Z < a)$$

---

### **Important Z-table Values:**

| Z | P(Z ≤ z) | | Z | P(Z ≤ z) |
|---|----------|---|---|----------|
| 0 | 0.5000 | | 1.645 | 0.9500 |
| 0.5 | 0.6915 | | 1.96 | 0.9750 |
| 1 | 0.8413 | | 2 | 0.9772 |
| 1.28 | 0.9000 | | 2.58 | 0.9950 |
| 1.5 | 0.9332 | | 3 | 0.9987 |

---

### **PROBLEM - Type 1: Finding Probability**

**Question:**

Heights are normally distributed with mean = 165 cm, S.D = 6 cm. Find probability that a student has height:

(a) Between 160 and 170 cm

(b) More than 175 cm

(c) Less than 158 cm

---

**SOLUTION:**

**Given:** μ = 165, σ = 6

---

**(a) P(160 < X < 170)**

**Step 1: Convert to Z**

For X = 160:

$$Z_1 = \frac{160 - 165}{6} = \frac{-5}{6} = -0.83$$

For X = 170:

$$Z_2 = \frac{170 - 165}{6} = \frac{5}{6} = 0.83$$

---

**Step 2: Find probability**

$$P(160 < X < 170) = P(-0.83 < Z < 0.83)$$

$$= P(Z < 0.83) - P(Z < -0.83)$$

**Using symmetry:**

$$P(Z < -0.83) = 1 - P(Z < 0.83)$$

So:

$$P(-0.83 < Z < 0.83) = P(Z < 0.83) - [1 - P(Z < 0.83)]$$

$$= 2P(Z < 0.83) - 1$$

From table: P(Z < 0.83) = 0.7967

$$= 2(0.7967) - 1 = 0.593$$

**ANSWER:** 0.593 or 59.3%

---

**(b) P(X > 175)**

**Step 1: Convert to Z**

$$Z = \frac{175 - 165}{6} = \frac{10}{6} = 1.67$$

---

**Step 2: Find probability**

$$P(X > 175) = P(Z > 1.67)$$

$$= 1 - P(Z < 1.67)$$

From table: P(Z < 1.67) = 0.9525

$$= 1 - 0.9525 = 0.0475$$

**ANSWER:** 0.048 or 4.8%

---

**(c) P(X < 158)**

**Step 1: Convert to Z**

$$Z = \frac{158 - 165}{6} = \frac{-7}{6} = -1.17$$

---

**Step 2: Find probability**

$$P(X < 158) = P(Z < -1.17)$$

$$= 1 - P(Z < 1.17)$$

From table: P(Z < 1.17) = 0.8790

$$= 1 - 0.8790 = 0.121$$

**ANSWER:** 0.121 or 12.1%

---

### **PROBLEM - Type 2: Finding Value (Inverse)**

**Question:**

Marks are normally distributed with mean = 70, S.D = 12. Find:

(a) Marks below which 90% students fall

(b) Marks above which top 5% students fall

---

**SOLUTION:**

**Given:** μ = 70, σ = 12

---

**(a) Find X such that P(X < x) = 0.90**

**Step 1: Find Z from table**

P(Z < z) = 0.90

From table: **z = 1.28**

---

**Step 2: Convert to X**

$$Z = \frac{X - \mu}{\sigma}$$

$$1.28 = \frac{X - 70}{12}$$

$$X - 70 = 1.28 \times 12 = 15.36$$

$$X = 85.36$$

**ANSWER:** 85.36 marks

---

**(b) Find X such that P(X > x) = 0.05**

**Step 1: Rewrite**

$$P(X > x) = 0.05$$

$$P(X < x) = 0.95$$

$$P(Z < z) = 0.95$$

From table: **z = 1.645**

---

**Step 2: Convert to X**

$$1.645 = \frac{X - 70}{12}$$

$$X - 70 = 19.74$$

$$X = 89.74$$

**ANSWER:** 89.74 marks (top 5% score above this)

---

### **PROBLEM - Type 3: Application**

**Question:**

IQ scores: mean = 100, S.D = 15. Find:

(a) % of people with IQ between 85 and 115

(b) IQ representing 75th percentile

---

**SOLUTION:**

---

**(a) P(85 < X < 115)**

For X = 85: Z₁ = (85-100)/15 = -1

For X = 115: Z₂ = (115-100)/15 = 1

$$P(85 < X < 115) = P(-1 < Z < 1)$$

$$= 2P(Z < 1) - 1$$

$$= 2(0.8413) - 1 = 0.6826$$

**ANSWER:** 68.26%

---

**(b) 75th percentile**

P(Z < z) = 0.75

From table: z = 0.674

$$0.674 = \frac{X - 100}{15}$$

$$X = 100 + 10.11 = 110.11$$

**ANSWER:** IQ = 110.11

---

## **🔟 GENERAL p.d.f PROBLEMS**

### **Standard Problem:**

**Question:**

p.d.f is:

$$f(x) = \begin{cases} kx^2 & 0 \leq x \leq 2 \\ 0 & \text{otherwise} \end{cases}$$

Find: (a) k (b) P(X > 1) (c) Mean

---

**SOLUTION:**

**(a) Find k**

**Use:** Total probability = 1

$$\int_0^2 kx^2 dx = 1$$

$$k\left[\frac{x^3}{3}\right]_0^2 = 1$$

$$k \times \frac{8}{3} = 1$$

$$k = \frac{3}{8}$$

---

**(b) P(X > 1)**

$$P(X > 1) = \int_1^2 \frac{3}{8}x^2 dx$$

$$= \frac{3}{8}\left[\frac{x^3}{3}\right]_1^2$$

$$= \frac{1}{8}[8 - 1] = \frac{7}{8}$$

---

**(c) Mean**

$$E(X) = \int_0^2 x \cdot \frac{3}{8}x^2 dx$$

$$= \frac{3}{8}\int_0^2 x^3 dx$$

$$= \frac{3}{8}\left[\frac{x^4}{4}\right]_0^2$$

$$= \frac{3}{8} \times 4 = \frac{3}{2}$$

**ANSWER:** Mean = 1.5

---

---

# **UNIT-I: BAYES' THEOREM (5 Marks)**

---

## **1️⃣1️⃣ BAYES' THEOREM**

### **Formula:**

$$P(A|B) = \frac{P(A) \cdot P(B|A)}{P(A) \cdot P(B|A) + P(A') \cdot P(B|A')}$$

For multiple events:

$$P(A_i|B) = \frac{P(A_i) \cdot P(B|A_i)}{\sum P(A_j) \cdot P(B|A_j)}$$

---

### **PROBLEM - Type 1: Two Machines**

**Question:**

Machine M₁ produces 60% of items, M₂ produces 40%.

M₁ has 3% defective, M₂ has 5% defective.

An item is defective. Find probability it's from M₁.

---

**SOLUTION:**

**Given:**
- P(M₁) = 0.6
- P(M₂) = 0.4
- P(D|M₁) = 0.03
- P(D|M₂) = 0.05

**Find:** P(M₁|D)

---

**Step 1: Total probability of defective**

$$P(D) = P(M_1) \cdot P(D|M_1) + P(M_2) \cdot P(D|M_2)$$

$$= 0.6 \times 0.03 + 0.4 \times 0.05$$

$$= 0.018 + 0.020 = 0.038$$

---

**Step 2: Apply Bayes' theorem**

$$P(M_1|D) = \frac{P(M_1) \cdot P(D|M_1)}{P(D)}$$

$$= \frac{0.6 \times 0.03}{0.038}$$

$$= \frac{0.018}{0.038}$$

$$= 0.474$$

**ANSWER:** Probability = 0.474 or 47.4%

---

### **PROBLEM - Type 2: Three Machines**

**Question:**

Machines A, B, C produce 30%, 45%, 25% of output.

Defective rates: 2%, 3%, 4% respectively.

(a) Find P(defective item)

(b) If defective, find P(from machine B)

---

**SOLUTION:**

**Given:**
- P(A) = 0.30, P(D|A) = 0.02
- P(B) = 0.45, P(D|B) = 0.03
- P(C) = 0.25, P(D|C) = 0.04

---

**(a) P(D)**

$$P(D) = 0.30(0.02) + 0.45(0.03) + 0.25(0.04)$$

$$= 0.006 + 0.0135 + 0.010$$

$$= 0.0295$$

**ANSWER:** 0.0295 or 2.95%

---

**(b) P(B|D)**

$$P(B|D) = \frac{0.45 \times 0.03}{0.0295}$$

$$= \frac{0.0135}{0.0295}$$

$$= 0.458$$

**ANSWER:** 0.458 or 45.8%

---

### **PROBLEM - Type 3: Urns**

**Question:**

Urn I: 3 white, 4 black balls

Urn II: 5 white, 3 black balls

One ball from I to II, then draw from II.

If drawn ball is white, find P(white was transferred).

---

**SOLUTION:**

**Let:**
- W₁ = white transferred
- B₁ = black transferred
- W₂ = white drawn from II

**Probabilities:**

$$P(W_1) = \frac{3}{7}, \quad P(B_1) = \frac{4}{7}$$

---

**After transfer:**

If W₁: Urn II has 6W, 3B

$$P(W_2|W_1) = \frac{6}{9} = \frac{2}{3}$$

If B₁: Urn II has 5W, 4B

$$P(W_2|B_1) = \frac{5}{9}$$

---

**Step 1: P(W₂)**

$$P(W_2) = \frac{3}{7} \times \frac{2}{3} + \frac{4}{7} \times \frac{5}{9}$$

$$= \frac{6}{21} + \frac{20}{63}$$

$$= \frac{18 + 20}{63} = \frac{38}{63}$$

---

**Step 2: P(W₁|W₂)**

$$P(W_1|W_2) = \frac{\frac{3}{7} \times \frac{2}{3}}{\frac{38}{63}}$$

$$= \frac{\frac{6}{21}}{\frac{38}{63}}$$

$$= \frac{6}{21} \times \frac{63}{38}$$

$$= \frac{18}{38} = \frac{9}{19}$$

**ANSWER:** 9/19 = 0.474

---

---

# **2-MARKS QUESTIONS (5 Marks)**

---

## **MUST LEARN DEFINITIONS**

### **Unit-V:**

**1. What is Null Hypothesis?**

The hypothesis being tested, usually stating "no difference" or "no effect". Denoted by H₀.

Example: H₀: μ = 50

---

**2. What is Alternative Hypothesis?**

The hypothesis that contradicts H₀. What we suspect is true. Denoted by H₁.

Example: H₁: μ ≠ 50

---

**3. Define Type I and Type II errors.**

**Type I Error (α):** Rejecting H₀ when it is actually true.

**Type II Error (β):** Accepting H₀ when it is actually false.

---

**4. What is Level of Significance?**

The probability of Type I error, denoted by α. Common values: 0.05, 0.01.

---

**5. When to use Z-test vs t-test?**

**Z-test:** When n ≥ 30 (large sample)

**t-test:** When n < 30 (small sample)

---

### **Unit-II:**

**6. State mean and variance of Binomial distribution.**

Mean = np

Variance = npq

---

**7. State mean and variance of Poisson distribution.**

Mean = λ

Variance = λ

(Mean = Variance)

---

**8. When to use Poisson approximation to Binomial?**

When:
- n is large (n ≥ 20)
- p is small (p ≤ 0.05)
- Use λ = np

---

### **Unit-IV:**

**9. State properties of correlation coefficient r.**

1. -1 ≤ r ≤ +1
2. r = +1: Perfect positive correlation
3. r = -1: Perfect negative correlation
4. r = 0: No linear correlation
5. r is independent of change of origin and scale

---

**10. What is the difference between correlation and regression?**

**Correlation:** Measures degree of relationship (how strong)

**Regression:** Predicts one variable from another (finds equation)

Correlation is symmetric, regression is not.

---

### **Unit-III:**

**11. Define continuous random variable.**

A random variable that can take any value in an interval (or intervals). 

Probabilities are found by integration.

---

**12. State properties of Normal distribution.**

1. Bell-shaped, symmetric about mean
2. Mean = Median = Mode = μ
3. Total area under curve = 1
4. 68% data within μ ± σ
5. 95% data within μ ± 2σ

---

### **Unit-I:**

**13. Define conditional probability.**

Probability of event A given that event B has occurred:

$$P(A|B) = \frac{P(A \cap B)}{P(B)}$$

---

**14. State Bayes' theorem.**

$$P(A|B) = \frac{P(A) \cdot P(B|A)}{P(A) \cdot P(B|A) + P(A') \cdot P(B|A')}$$

---

**15. Define independent events.**

Events A and B are independent if:

$$P(A \cap B) = P(A) \cdot P(B)$$

Or equivalently: P(A|B) = P(A)

---

---

# **📋 FINAL CHECKLIST - 60+ MARKS**

---

## **FORMULAS TO MEMORIZE:**

### **Unit-V (Must Know!):**

☑️ Z (proportion) = (p - P)/√(PQ/n)

☑️ Z (mean) = (x̄ - μ)/(σ/√n)

☑️ Z (diff means) = (x̄₁ - x̄₂)/√(σ₁²/n₁ + σ₂²/n₂)

☑️ t = (x̄ - μ)/(s/√n)

☑️ Pooled variance = [(n₁-1)s₁² + (n₂-1)s₂²]/(n₁+n₂-2)

☑️ Critical values: 1.96, 2.58, 1.645, 2.33

---

### **Unit-II (Must Know!):**

☑️ P(X=r) = C(n,r) × p^r × q^(n-r)

☑️ Mean = np, Variance = npq

☑️ Poisson: P(X=r) = (e^(-λ) × λ^r)/r!

☑️ e^(-1) = 0.3679, e^(-2) = 0.1353, e^(-3) = 0.0498

---

### **Unit-IV (Must Know!):**

☑️ r = [nΣxy - ΣxΣy]/√[...] 

☑️ b_yx = [nΣxy - ΣxΣy]/[nΣx² - (Σx)²]

☑️ b = same numerator / [nΣx² - (Σx)²] for straight line

☑️ a = (Σy - bΣx)/n

---

### **Unit-III (Must Know!):**

☑️ Z = (X - μ)/σ

☑️ Important Z-values: 0.8413 (Z=1), 0.9772 (Z=2)

---

---

## **PRACTICE PROBLEMS COUNT:**

☑️ Unit-V: 5 problems (1 each type)

☑️ Unit-II: 4 problems (2 binomial, 2 Poisson)

☑️ Unit-IV: 4 problems (2 correlation/regression, 2 straight line)

☑️ Unit-III: 3 problems (2 normal, 1 p.d.f)

☑️ Unit-I: 2 Bayes problems

☑️ 2-marks: 15 definitions

---

## **TIME ALLOCATION IN EXAM:**

- Unit-V question: 30 minutes
- Unit-II question: 25 minutes
- Unit-IV question: 30 minutes
- Unit-III question: 25 minutes
- Unit-I question: 20 minutes
- 2-marks (5 questions): 15 minutes
- Revision: 15 minutes

**Total: 160 minutes (well within 180 minutes)**

---

## **🎯 FINAL TIPS:**

✅ **Write all steps** - even if answer wrong, get partial marks

✅ **Underline formulas** - shows you know the concept

✅ **Make tables** neat in correlation/regression

✅ **Write H₀, H₁** clearly in hypothesis tests

✅ **Show calculation** clearly - don't skip steps

✅ **Write conclusion** in words for hypothesis tests

✅ **Use calculator** carefully - most errors are calculation mistakes

✅ **Check units** - don't mix percentages and decimals

---

**Bro, ee material tho 60+ guaranteed! 💯**

**Focus, practice, and score maximum! All the best! 🔥💪**

Doubts unte adugu! 😊
