# Sales Navigator Search Data Scraper ⚡ No Cookies ✅

If you want use it try it out [here](https://apify.com/pratikdani/sales-navigator-search-scraper-no-cookies).

This Sales Navigator Search Scraper ⚡ No Cookies ✅ is a powerful tool designed to efficiently extract comprehensive contact and company data directly from Sales Navigator search results, eliminating the need for cookies and simplifying integration. It meticulously collects essential information such as individual profiles (names, titles, company affiliations, contact details, recent activity), company details (industry, size, location, growth trends), and sales intelligence insights (deal stages, engagement metrics, relevant keywords). This data is invaluable for sales professionals, marketers, and researchers seeking to identify, qualify, and engage with high-potential leads, personalize outreach strategies, build targeted prospect lists, and gain a competitive edge by understanding market dynamics and prospect needs within their sales workflows.

## Features

*   Extracts comprehensive lead and account data directly from Sales Navigator search results.
*   Uncovers targeted prospects for sales outreach, lead generation, and market research.
*   Enables the efficient building of custom prospect lists for personalized campaigns.
*   Automates data gathering, saving significant manual effort and time for sales teams.
*   Provides up-to-date contact information and company details for accurate targeting.
*   Supports rapid identification of ideal customer profiles and potential new markets.

## Output Fields

| Field Name                       | Type           | Description                                                                                                                                             |
| :------------------------------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `firstName`                      | String         | The first name of the person.                                                                                                                           |
| `fullName`                       | String         | The full name of the person.                                                                                                                            |
| `lastName`                       | String         | The last name of the person.                                                                                                                            |
| `geoRegion`                      | String         | The geographical region where the person is located.                                                                                                    |
| `currentPosition.tenureAtPosition.numYears` | Integer        | The number of years the person has held their current position.                                                                                         |
| `currentPosition.tenureAtPosition.numMonths` | Integer        | The number of months the person has held their current position.                                                                                        |
| `currentPosition.companyName`    | String         | The name of the company where the person currently works.                                                                                               |
| `currentPosition.description`    | String         | A brief description of the person's role or responsibilities at their current position.                                                                 |
| `currentPosition.title`          | String         | The job title of the person's current position.                                                                                                         |
| `currentPosition.companyId`      | String         | The unique identifier for the company.                                                                                                                  |
| `currentPosition.companyUrnResolutionResult.name` | String         | The resolved name of the company.                                                                                                       |
| `currentPosition.companyUrnResolutionResult.companyPictureDisplayImage` | String         | The URL of the company's logo.                                                                                                          |
| `currentPosition.companyUrnResolutionResult.industry` | String         | The industry the company operates in.                                                                                                   |
| `currentPosition.companyUrnResolutionResult.location` | String         | The location of the company.                                                                                                            |
| `currentPosition.current`        | Boolean        | Indicates if this is the person's current position (true/false).                                                                                       |
| `currentPosition.tenureAtCompany.numYears` | Integer        | The number of years the person has been employed at the company.                                                                                        |
| `currentPosition.tenureAtCompany.numMonths` | Integer        | The number of months the person has been employed at the company.                                                                                       |
| `currentPosition.startedOn.month` | Integer        | The month the person started their current position.                                                                                                    |
| `currentPosition.startedOn.year`  | Integer        | The year the person started their current position.                                                                                                     |
| `profilePictureDisplayImage`     | String         | The URL of the person's profile picture.                                                                                                                |
| `summary`                        | String         | A brief summary or bio of the person.                                                                                                                   |
| `profileUrn`                     | String         | The unique identifier for the person's LinkedIn profile.                                                                                                |
| `navigationUrl`                  | String         | The direct URL to the person's LinkedIn profile.                                                                                                        |
| `openLink`                       | Boolean        | Indicates if the LinkedIn profile link is intended to be opened in a new tab (true/false).                                                              |

## Possible Usage of the Actor

*   **Lead Generation & Prospecting:** Identify and export lists of companies or individuals meeting specific criteria (industry, location, job title, technology used, growth metrics) for targeted outreach campaigns.
*   **Competitive Intelligence:** Track competitors' hiring trends, recent funding rounds, or expansions by monitoring companies and their employee movements or company updates.
*   **Market Research & Trend Analysis:** Gather data on companies adopting specific technologies, expanding into new markets, or exhibiting certain growth patterns to identify emerging trends.
*   **Account-Based Marketing (ABM) List Building:** Create highly targeted lists of key decision-makers within target accounts for personalized ABM campaigns.
*   **Sales Territory Planning & Optimization:** Analyze prospect density and potential within specific geographical regions or industries to optimize sales territory assignments.
*   **Talent Acquisition Scouting:** Identify companies hiring for specific roles or in high-growth sectors to understand the talent landscape and potential candidate pools.

## Example Output
```json
{
  "firstName": "Kyohwe",
  "fullName": "Kyohwe Goo",
  "lastName": "Goo",
  "geoRegion": "South Korea",
  "currentPosition": {
    "tenureAtPosition": {
      "numYears": 5,
      "numMonths": 5
    },
    "companyName": "Hyundai Motor Company",
    "description": "Career that combines design, strategy and storytelling to support great products",
    "title": "Design Strategy",
    "companyId": "825160",
    "companyUrnResolutionResult": {
      "name": "Hyundai Motor Company",
      "companyPictureDisplayImage": "https://media.licdn.com/dms/image/v2/D560BAQGdH5q8Y1WS4Q/company-logo_200_200/company-logo_200_200/0/1727213210065/hyundai_motor_company_logo?e=1761782400&v=beta&t=d5avnlfJvaXONkmeWl_4ilIZ-T1Pe-xgMJeNir4Scn8",
      "industry": "Motor Vehicle Manufacturing",
      "location": "Seoul, Seoul, South Korea"
    },
    "current": true,
    "tenureAtCompany": {
      "numYears": 5,
      "numMonths": 5
    },
    "startedOn": {
      "month": 5,
      "year": 2020
    }
  },
  "profilePictureDisplayImage": "https://media.licdn.com/dms/image/v2/C5603AQHxHEwsdVIcZQ/profile-displayphoto-shrink_100_100/profile-displayphoto-shrink_100_100/0/1627174763212?e=1761782400&v=beta&t=p831zBK5G_ux-G7oSVrS6BpdE7ub9Bb1Su-EQKP9ojc",
  "summary": "Studied mechanical engineering, industrial/transportation design to create innovative solutions for future automotive/mobility design",
  "profileUrn": "ACwAACc_JjIBSeHOEA2truT7un1QADxUExNCuoY",
  "navigationUrl": "https://www.linkedin.com/in/ACwAACc_JjIBSeHOEA2truT7un1QADxUExNCuoY",
  "openLink": false
}
```
