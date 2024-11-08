### LinkedIn Profile Scraper

This actor can scrape detailed information about LinkedIn profiles without any hassle. It takes profile URLs and provides you with structured data. You can scrape a single URL or a list of URLs.
[likedin-profile-scraper](https://apify.com/logical_scrapers/linkedin-profile-scraper)

### How It Works

The LinkedIn Profile Scraper allows you to gather comprehensive information from LinkedIn profile pages. Simply provide the URLs of the profiles you want to scrape, and the actor will fetch the data for you. This scraper is perfect for data analysis, research, and gaining insights from LinkedIn profiles.

### What Data You Can Get from This Scraper (showing 8 of 35 fields)

| Field                        | Description                                               |
|------------------------------|-----------------------------------------------------------|
| 📝 summary                   | The summary or bio of the profile                         |
| 💼 headline                  | The professional headline or current role                 |
| 🏢 industryName              | The industry the person works in                          |
| 📍 locationName              | The location or city where the person is based            |
| 💻 experience                | The person's work experience, including company names, job titles, dates, and descriptions |
| 🎓 education                 | The person's educational background, including schools, degrees, and fields of study |
| 🏆 certifications            | The certifications or licenses the person has obtained    |
| 🧠 skills                    | The skills or expertise areas listed on the profile       |

### Input

Provide a valid LinkedIn profile URLs.

Example:
```
 "https://www.linkedin.com/in/johndoe" 

```

## Output 
(showing all 35 fields)

```
[
  {
    "summary": "Enthusiastic full stack developer with a degree in computer engineering. Experienced in designing and developing web and mobile applications, including projects for banks with thousands of users. Passionate about integrating machine learning and AI into software. Committed to continuous learning and delivering high-quality solutions, bringing strong problem-solving and collaboration skills to dynamic teams.",
    "industryName": "Computer Software",
    "lastName": "Mesfin",
    "locationName": "Ethiopia",
    "student": false,
    "geoCountryName": "Ethiopia",
    "geoCountryUrn": "urn:li:fs_geo:100212432",
    "geoLocationBackfilled": false,
    "elt": false,
    "industryUrn": "urn:li:fs_industry:4",
    "firstName": "Daniel",
    "entityUrn": "urn:li:fs_profile:ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94",
    "geoLocation": {
      "geoUrn": "urn:li:fs_geo:103636250"
    },
    "geoLocationName": "Addis Ababa",
    "location": {
      "basicLocation": {
        "countryCode": "et"
      }
    },
    "headline": "Software Engineer at Arez Armada | Fullstack developer | ML Engineer",
    "displayPictureUrl": "https://media.licdn.com/dms/image/D4D03AQGTegeVUIZqaA/profile-displayphoto-shrink_",
    "img_100_100": "100_100/0/1702538073848?e=1725494400&v=beta&t=1zsxTQ5-_Ph11BmQxCmUEYLTn64yT_LRM2OxOAh90UQ",
    "img_200_200": "200_200/0/1702538073848?e=1725494400&v=beta&t=44wCPKad8oj6D2kyU2ip-RDLMGVmBGwW0N-3ZrQuyd4",
    "img_400_400": "400_400/0/1702538073848?e=1725494400&v=beta&t=IBsfw1_dmYj-3ZurKqej-LVclwr5PtU2xMpJjIAGKPk",
    "img_576_576": "800_800/0/1702538073848?e=1725494400&v=beta&t=Y8Pv17xavih4U4okrzEDtj9uw024NWt6_tUHWrDCcts",
    "profile_id": "ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94",
    "profile_urn": "urn:li:fs_miniProfile:ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94",
    "member_urn": "urn:li:member:890710496",
    "public_id": "danielmesfin",
    "experience": [
      {
        "locationName": "United States",
        "entityUrn": "urn:li:fs_position:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,2337455461)",
        "geoLocationName": "United States",
        "geoUrn": "urn:li:fs_geo:103644278",
        "companyName": "Arez Armada",
        "timePeriod": {
          "startDate": {
            "month": 12,
            "year": 2023
          }
        },
        "company": {
          "employeeCountRange": {
            "start": 51,
            "end": 200
          },
          "industries": [
            "Computer Software"
          ]
        },
        "title": "Project Manager",
        "region": "urn:li:fs_region:(us,0)",
        "companyUrn": "urn:li:fs_miniCompany:98911981",
        "companyLogoUrl": "https://media.licdn.com/dms/image/D4E0BAQF8zchtb1Damw/company-logo_"
      },
      {
        "locationName": "United States",
        "entityUrn": "urn:li:fs_position:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,2275726909)",
        "geoLocationName": "United States",
        "geoUrn": "urn:li:fs_geo:103644278",
        "companyName": "Arez Armada",
        "timePeriod": {
          "startDate": {
            "month": 10,
            "year": 2023
          }
        },
        "company": {
          "employeeCountRange": {
            "start": 51,
            "end": 200
          },
          "industries": [
            "Computer Software"
          ]
        },
        "title": "Software Engineer",
        "region": "urn:li:fs_region:(us,0)",
        "companyUrn": "urn:li:fs_miniCompany:98911981",
        "companyLogoUrl": "https://media.licdn.com/dms/image/D4E0BAQF8zchtb1Damw/company-logo_"
      },
      {
        "locationName": "Addis Ababa, Ethiopia",
        "entityUrn": "urn:li:fs_position:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,2153677865)",
        "geoLocationName": "Addis Ababa, Ethiopia",
        "geoUrn": "urn:li:fs_geo:103636250",
        "companyName": "Minnovation",
        "timePeriod": {
          "endDate": {
            "month": 2,
            "year": 2024
          },
          "startDate": {
            "month": 4,
            "year": 2023
          }
        },
        "company": {
          "employeeCountRange": {
            "start": 51,
            "end": 200
          },
          "industries": [
            "Consumer Electronics"
          ]
        },
        "title": "Software Engineer",
        "region": "urn:li:fs_region:(et,0)",
        "companyUrn": "urn:li:fs_miniCompany:89554331",
        "companyLogoUrl": "https://media.licdn.com/dms/image/D560BAQGgAqkGUpxBYA/company-logo_"
      },
      {
        "entityUrn": "urn:li:fs_position:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,2146092421)",
        "companyName": "UnitCodex",
        "timePeriod": {
          "endDate": {
            "month": 3,
            "year": 2023
          },
          "startDate": {
            "month": 1,
            "year": 2023
          }
        },
        "title": "Full Stack Web App Developer"
      },
      {
        "locationName": "Addis Ababa",
        "entityUrn": "urn:li:fs_position:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,1936768320)",
        "geoLocationName": "Addis Ababa",
        "companyName": "EagleLion System Technology",
        "timePeriod": {
          "endDate": {
            "month": 1,
            "year": 2023
          },
          "startDate": {
            "month": 3,
            "year": 2022
          }
        },
        "company": {
          "employeeCountRange": {
            "start": 11,
            "end": 50
          },
          "industries": [
            "Information Technology and Services"
          ]
        },
        "title": "Frontend Developer",
        "companyUrn": "urn:li:fs_miniCompany:79709708",
        "companyLogoUrl": "https://media.licdn.com/dms/image/C4D0BAQHpegS0uq8nLg/company-logo_"
      }
    ],
    "education": [
      {
        "entityUrn": "urn:li:fs_education:(ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94,715039316)",
        "school": {
          "objectUrn": "urn:li:school:12265",
          "entityUrn": "urn:li:fs_miniSchool:12265",
          "active": true,
          "schoolName": "Addis Ababa University",
          "trackingId": "PDfi55x6S5+uQqp6UVwb3A==",
          "logoUrl": "https://media.licdn.com/dms/image/C4E0BAQFzFF_6HzIPow/company-logo_"
        },
        "timePeriod": {
          "endDate": {
            "year": 2023
          },
          "startDate": {
            "year": 2019
          }
        },
        "degreeName": "Electrical Engineering",
        "schoolName": "Addis Ababa University",
        "fieldOfStudy": "Computer Engineering",
        "schoolUrn": "urn:li:fs_miniSchool:12265"
      }
    ],
    "languages": [],
    "publications": [],
    "certifications": [
      {
        "authority": "NVIDIA",
        "name": "Getting Started with Deep Learning",
        "timePeriod": {
          "startDate": {
            "month": 8,
            "year": 2022
          }
        },
        "licenseNumber": "35e66496eec64fb6a3163cceaf20a738",
        "company": {
          "objectUrn": "urn:li:company:3608",
          "entityUrn": "urn:li:fs_miniCompany:3608",
          "name": "NVIDIA",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=xsinjTZsYh6Ykg5MYhqm5y_P0L1Xo_6vFinX68vTNZY",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=8dbH6Sk5QevOHGzuDjHSTht7si-TRbgJNVB13I269uk",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=5UWk9I20l8Wh97Em3GEfkOXBj-6WF3lQoHz-HGQdkqU",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C560BAQFDs6GbpvE3zA/company-logo_"
            }
          },
          "universalName": "nvidia",
          "dashCompanyUrn": "urn:li:fsd_company:3608",
          "trackingId": "hCfwdL2STsOARP0rOxHFXw=="
        },
        "displaySource": "nvidia.com",
        "companyUrn": "urn:li:fs_miniCompany:3608",
        "url": "https://courses.nvidia.com/certificates/35e66496eec64fb6a3163cceaf20a738/"
      },
      {
        "authority": "NVIDIA",
        "name": "Building Real-Time Video AI Applications",
        "timePeriod": {
          "startDate": {
            "month": 9,
            "year": 2022
          }
        },
        "licenseNumber": "f44c2824a7664c09941a1d507871765d",
        "company": {
          "objectUrn": "urn:li:company:3608",
          "entityUrn": "urn:li:fs_miniCompany:3608",
          "name": "NVIDIA",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=xsinjTZsYh6Ykg5MYhqm5y_P0L1Xo_6vFinX68vTNZY",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=8dbH6Sk5QevOHGzuDjHSTht7si-TRbgJNVB13I269uk",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630584931971/nvidia_logo?e=1727913600&v=beta&t=5UWk9I20l8Wh97Em3GEfkOXBj-6WF3lQoHz-HGQdkqU",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C560BAQFDs6GbpvE3zA/company-logo_"
            }
          },
          "universalName": "nvidia",
          "dashCompanyUrn": "urn:li:fsd_company:3608",
          "trackingId": "bv/zKF7MQaSIsazVL3fqmA=="
        },
        "displaySource": "nvidia.com",
        "companyUrn": "urn:li:fs_miniCompany:3608",
        "url": "https://courses.nvidia.com/certificates/f44c2824a7664c09941a1d507871765d/"
      },
      {
        "authority": "Sololearn",
        "name": "JavaScript Specialist Certification",
        "timePeriod": {
          "startDate": {
            "month": 5,
            "year": 2020
          }
        },
        "licenseNumber": "CT-STSGSKV6",
        "company": {
          "objectUrn": "urn:li:company:9435690",
          "entityUrn": "urn:li:fs_miniCompany:9435690",
          "name": "Sololearn",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=TYBYafzCeKEhVNozU7-AOLFLJZPj3ewrYPuNHnBnl3k",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=1NlH0TPCdUqpwQkOQkc2Tv3wNUdduyvVBrRSoQgTNdQ",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=rpygyNIjnRSBMq8VE8RUmw2t15j6_oSIFmpd0YGr8Vo",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C4D0BAQHER-dvTqh2tA/company-logo_"
            }
          },
          "universalName": "sololearn-inc-",
          "dashCompanyUrn": "urn:li:fsd_company:9435690",
          "trackingId": "2B30PXCtTh238F+XXxrj5g=="
        },
        "displaySource": "sololearn.com",
        "companyUrn": "urn:li:fs_miniCompany:9435690",
        "url": "https://www.sololearn.com/certificates/CT-STSGSKV6"
      },
      {
        "authority": "Sololearn",
        "name": "PHP",
        "timePeriod": {
          "startDate": {
            "month": 3,
            "year": 2021
          }
        },
        "licenseNumber": "CT-SSKK6NFE",
        "company": {
          "objectUrn": "urn:li:company:9435690",
          "entityUrn": "urn:li:fs_miniCompany:9435690",
          "name": "Sololearn",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=TYBYafzCeKEhVNozU7-AOLFLJZPj3ewrYPuNHnBnl3k",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=1NlH0TPCdUqpwQkOQkc2Tv3wNUdduyvVBrRSoQgTNdQ",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=rpygyNIjnRSBMq8VE8RUmw2t15j6_oSIFmpd0YGr8Vo",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C4D0BAQHER-dvTqh2tA/company-logo_"
            }
          },
          "universalName": "sololearn-inc-",
          "dashCompanyUrn": "urn:li:fsd_company:9435690",
          "trackingId": "UVOGWZn1TXGt4oKw3MmIGw=="
        },
        "displaySource": "sololearn.com",
        "companyUrn": "urn:li:fs_miniCompany:9435690",
        "url": "https://www.sololearn.com/certificates/CT-SSKK6NFE"
      },
      {
        "authority": "Sololearn",
        "name": "HTML",
        "timePeriod": {
          "startDate": {
            "month": 11,
            "year": 2019
          }
        },
        "licenseNumber": "CT-ULXCNDLY",
        "company": {
          "objectUrn": "urn:li:company:9435690",
          "entityUrn": "urn:li:fs_miniCompany:9435690",
          "name": "Sololearn",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=TYBYafzCeKEhVNozU7-AOLFLJZPj3ewrYPuNHnBnl3k",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=1NlH0TPCdUqpwQkOQkc2Tv3wNUdduyvVBrRSoQgTNdQ",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630576160230/sololearn_inc__logo?e=1727913600&v=beta&t=rpygyNIjnRSBMq8VE8RUmw2t15j6_oSIFmpd0YGr8Vo",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C4D0BAQHER-dvTqh2tA/company-logo_"
            }
          },
          "universalName": "sololearn-inc-",
          "dashCompanyUrn": "urn:li:fsd_company:9435690",
          "trackingId": "g5ejumSxR6K5zhHylwh/BQ=="
        },
        "displaySource": "sololearn.com",
        "companyUrn": "urn:li:fs_miniCompany:9435690",
        "url": "https://www.sololearn.com/certificates/CT-ULXCNDLY"
      },
      {
        "authority": "Coursera",
        "name": "Build a website with WordPress",
        "timePeriod": {
          "startDate": {
            "month": 12,
            "year": 2023
          }
        },
        "company": {
          "objectUrn": "urn:li:company:2453129",
          "entityUrn": "urn:li:fs_miniCompany:2453129",
          "name": "Coursera",
          "showcase": false,
          "active": true,
          "logo": {
            "com.linkedin.common.VectorImage": {
              "artifacts": [
                {
                  "width": 200,
                  "fileIdentifyingUrlPathSegment": "200_200/0/1630530042036/coursera_logo?e=1727913600&v=beta&t=zQNoKhQ0wTDjgiZX6soFiJSn1smQNrW3ZDZzmKGAcFE",
                  "expiresAt": 1727913600000,
                  "height": 200
                },
                {
                  "width": 100,
                  "fileIdentifyingUrlPathSegment": "100_100/0/1630530042036/coursera_logo?e=1727913600&v=beta&t=ReZIycyQFcy9TUdbz1JtInol_WVWUDMpzxGnztvDOVg",
                  "expiresAt": 1727913600000,
                  "height": 100
                },
                {
                  "width": 400,
                  "fileIdentifyingUrlPathSegment": "400_400/0/1630530042036/coursera_logo?e=1727913600&v=beta&t=KwR1gk6n24RAKBuhqAZ0CI9T-pykBYTQqv8Csfm-A6o",
                  "expiresAt": 1727913600000,
                  "height": 400
                }
              ],
              "rootUrl": "https://media.licdn.com/dms/image/C4D0BAQGexnfBxeEG-g/company-logo_"
            }
          },
          "universalName": "coursera",
          "dashCompanyUrn": "urn:li:fsd_company:2453129",
          "trackingId": "omx97TCLTMulUIwfOA+aMg=="
        },
        "displaySource": "coursera.org",
        "companyUrn": "urn:li:fs_miniCompany:2453129",
        "url": "https://coursera.org/share/bed13da36f138a1a26635d3b3a10b2ec"
      }
    ],
    "volunteer": [],
    "honors": [],
    "projects": [],
    "skills": [
      {
        "name": "Google Cloud Platform (GCP)"
      },
      {
        "name": "Next.js"
      },
      {
        "name": "Cross-functional Team Leadership"
      },
      {
        "name": "Event Planning"
      }
    ],
    "urn_id": "ACoAADUXKeABxR-S4T48uTvHl7SxLnNRWUJdU94"
  }
]
```

If you have any feature requests or encounter any bugs, please feel free to create an issue. Your feedback is highly appreciated and helps us improve the actor.
