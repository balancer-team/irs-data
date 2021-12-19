# IRS Data

IRS data in a variety of formats. Data is obtained from the official IRS website.

## Contents

#### Tax Rates on Income Other Than Personal Service Income Under Chapter 3, Internal Revenue Code, and Income Tax Treaties (Rev. Feb 2019)

Available Files:

- `csv/tax-treaty-rates-2019-02.csv`
- `json/tax-treaty-rates-2019-02.json`
- `pdf/tax-treaty-rates-2019-02.pdf`

This data lists the income tax rates on interest, dividends, royalties, and other income that is not effectively connected with the conduct of a U.S. trade or business. The income code numbers shown in this table are the same as the income codes on Form 1042-S, Foreign Person's U.S. Source Income Subject to Withholding.

The IRS `.pdf` file includes several treaties with a 30% rate. However, 30% is the default withholding rate regardless of treaty status, so we have excluded these treaties from the `.csv` and `.json` files.
