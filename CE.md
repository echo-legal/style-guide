# Contract Express Style Guide

## Table of contents

Section                     |Contents
----------------------------|----------------
[Naming conventions](#s1-NamingConventions)   |Variables - Template references
[Automation markup](#s2-Markup)   |Markup brackets - Colors
[Best practice](#s3-BestPractice) | Indents

<a id="s1-NamingConventions"></a>

## Naming conventions

<a id="s1-1-Variables"></a>

### Variable names

1. Question Variables - no spaces, use caps to separate words \([CamelCase](https://en.wikipedia.org/wiki/Camel_case)\):

    * `BorrowerName`
    * `AgreementDate`
    * `MonthlyPayment`

2. Calculations (variable type Computable) which return values other than true/false follow the same principle:

    * `AnnualPaymentCalculation`
    
3. Computable variables, used in spans to control additional woridng so will evaluate to true or false: all caps, underscores to separate words. Try to include a verb to phrase as a question:

    * `HAS_MULTI_BORROWERS` 
    * `HAS_SINGLE_CORPORATE_BORROWER`
    * `INCLUDE_OPTIONAL_WORDING`
    *  `USE_LONDON_TIME`

<a id="s1-2-Templates"></a>

### Template references

1. Spaces in references are allowed, so should be used to make them easier to read. Avoid including client names in the references.

    * `On Demand Offer Letter`
    * `HR Terms of Employment`

<a id="s2-Markup"></a>

## Automation markup

1. The echo.legal default markup brackets are:

    * `<>` for spans
    * `{}` for fields

2. Use *default colours* for highlighting markup. Do not change these colours to keep consistency.

    Default colours are (values given in HEX):
    * Fields: `#0000FF`
    * Span brackets: `#FF4500`
    * Business rules: `#800000`

3. Spell Check entire dictionary before delivery.

<a id="s3-BestPractice"></a>

## Best practice

### Indents

1. When working on a particularly long piece of code in a computable (3+ functions, 5+ lines), consider adding line breaks and indents to show where functions and properties start and end.

    You can use tools like [CE code indenter](https://kgeorgiadis-law.github.io/ce-formatter/) to automatically indent your code.
