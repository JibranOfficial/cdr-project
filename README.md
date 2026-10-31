# CDR Analysis: A Simple Guide

## What is this?

CDR Analysis is a small tool that reads a **call record spreadsheet** (the kind a phone company provides, called a CDR, or Call Detail Record) and tells you, in plain terms:

- **Who was contacted the most**
- Their **phone number**
- **When** the calls happened (time of day, dates)
- A **full ranking** of everyone, from most calls to least

You do not need to install anything or know how to code. It is a single file that opens in your web browser.

## Is my data safe?

Yes. The file you choose is read **only inside the page on your own computer**. Nothing is uploaded to the internet and nothing is saved. When you close the page, it is gone.

## What you need

- A computer with a web browser (Chrome, Edge, Firefox or Safari)
- Your call record file in one of these formats: **.xlsx, .xls, .csv or .tsv**
- The file `CDR_ANALYSIS.html`

## How to use it

### Step 0: Open the tool
Double-click `CDR_ANALYSIS.html`. It opens in your browser. (An internet connection is needed the first time so the page can load its fonts and spreadsheet reader.)

### Step 1: Load the file (blue box)
- Click **Choose an Excel or CSV file**, or drag your file onto the box.
- If the file has several sheets, pick the right one from the **Sheet** list.
- If the column titles (like "Date", "Number") are not on the first row, enter the correct row number in **Column names are on row**.
- Just want to try it? Click **Load example data** to see how it works with sample calls.

### Step 2: Choose the columns (blue box)
The page tries to guess what each column means. Check each guess and fix it if needed, for example:
- Which column is the **phone number**
- Which is the **contact name** (if there is one)
- Which is the **date and time**
- Which is the **call length**
- Which is the **location**

Anything you do not need can be set to **Ignore**.
You must choose at least the **phone number** or the **contact name**.

Optional filters:
- **Call type**: for example, only outgoing or only incoming calls
- **From date / To date**: only look at a certain period

### Step 3: Read the ranking (red section)
The results appear automatically:

| What you see | What it means |
|---|---|
| **Calls analysed** | How many calls were read |
| **Different contacts** | How many different people or numbers appear |
| **Total talk time** | All call time added together |
| **Date range** | The first and last day in the file |
| **Most contacted** | The top person: their number, how many calls, first and last call, total and average call length, and most common location |
| **When the calls happen** | A small bar chart of the busiest hours of the day (the tallest, yellow bar is the busiest) |
| **Every call with this contact** | A scrollable table of each call with date, time, length and location |
| **Everyone else, most to least** | The full ranking of the remaining contacts, with a bar showing how they compare |

## Copying your results

- **Copy history** copies the top contact's call list so you can paste it into Word, Excel or an email.
- **Copy full ranking** copies the whole ranking.
- If the copy button does not work in your browser, use the **Select all and copy** box at the bottom of the page and copy from there.

## Tips and common problems

- **Nothing happens after choosing my file.** Make sure it is an Excel or CSV file, not a PDF or photo.
- **The numbers look wrong.** Go back to Step 2 and check that each column is matched correctly, and that the title row number in Step 1 is right.
- **Some contacts show 0s for call length.** Those were missed or unanswered calls, which is normal in call records.
- **I want to start over.** Refresh the page and load your file again.

## Good to know

This tool only **summarises** the records you give it. It cannot tell you who a number belongs to unless a name is already in your file. Please use call records only where you have the right to do so.
