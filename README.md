# NPV_PROJECT

**Asset Management Company Dataset**

The Objective is to identify the best countries and a suitable investment type for making the
investment. The overall strategy is to invest where others are investing, implying that the best
countries are the ones ‘where most investors are investing’

Dataset Schema given below,

**Companies Details**

Attributes Description:

    Permalink Unique ID of Companies
    name name of Companies
    homeurl_page Website URL
    Category_list Categories to which company belong
    Status Operational Status
    country_code country_code
    state_code state

**rounds2**

Attributes Description:

    company_permalink Unique ID of company
    funding_round_permalink Unique ID of funding round
    funding_round_type Type of funding - Venture,angel, private equity
    funding_round_code Round of venture funding (round A,B..)
    Funding_at Date of funding
    raised_amount_usd Money raised in funding (USD)


