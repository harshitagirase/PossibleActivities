# Tax Rates & Conditionals

Given the following code snippet, what would each individual owe in taxes?

```java
int taxOwed = 0;

if (income > 10000) {
    taxOwed = taxOwed + 500;
    if (income > 25000) {
        taxOwed = taxOwed + 15000 * 0.15;
        if (income > 50000) {
            taxOwed = taxOwed + (25000 * 0.3) + (income - 50000) * 0.40;
        } else {
	           taxOwed = taxOwed + (income - 25000) * 0.3;
        }
    } else {
        taxOwed = taxOwed + (income - 10000) * 0.15;
    }
} else {
    taxOwed = taxOwed + income * 0.05;
}

if (married) {
    if (ownHome) {
		    taxOwed = taxOwed * 0.95;
    } else {
		    taxOwed = taxOwed - 400;
    }
}
```

#### Person A:
- Income - 12,000
- Single
- Owns Home

#### Person B:
- Income - 70000
- Married
- Rents Apartment

#### Person C:
- Income - 30000
- Married
- Owns Home

## Follow Up
Can you describe the tax rate scheme in English (can include diagrams and tables if helpful)?

----

**Solid Understanding**: Create a small table to descirbe tax brackets with a sentence or two mentioning how being married or owning a home affects your tax rate correctly. Show understanding that income is progressively taxes (your income up to increasing levels is taxed at increasing rates)

**Vague Understanding**: Explain that the more you make the more you are taxed, but without any mention of a progressive system. Mention that you pay less taxes if you are married or have a home, but no mention of the fact that if you own a home, but aren’t married you don’t get any benefit.

**Lack of or Minimal Understanding**: Either doesn’t mention that people pay more taxes when they make more money or say that as you pay more you pay less in taxes. No mention or incorrect explanation of the effect of marital status and home ownership on the amount owed in taxes.
