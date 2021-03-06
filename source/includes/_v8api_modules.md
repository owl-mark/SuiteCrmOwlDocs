## API modules
### Accounts

客戶

#### Create Leads

`POST http://example.com/Api/V8/module`

```json--request

{
    "data": {
        "type": "Accounts",
        "attributes": {
            "name": "test",
            "date_entered": "2021-05-04T07:38:00+00:00",
            "date_modified": "2021-05-04T07:38:00+00:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "SecurityGroups": "",
            "account_type": "^Analyst^",
            "industry": "",
            "annual_revenue": "",
            "phone_fax": "",
            "billing_address_street": "",
            "billing_address_street_2": "",
            "billing_address_street_3": "",
            "billing_address_street_4": "",
            "billing_address_city": "",
            "billing_address_state": "",
            "billing_address_postalcode": "",
            "billing_address_country": "tw",
            "rating": "",
            "phone_office": "",
            "phone_alternate": "",
            "website": "",
            "ownership": "",
            "employees": "",
            "ticker_symbol": "",
            "shipping_address_street": "",
            "shipping_address_street_2": "",
            "shipping_address_street_3": "",
            "shipping_address_street_4": "",
            "shipping_address_city": "",
            "shipping_address_state": "",
            "shipping_address_postalcode": "",
            "shipping_address_country": "tw",
            "email1": "",
            "email_addresses_primary": "",
            "email_addresses": "",
            "email_addresses_non_primary": "",
            "parent_id": "",
            "sic_code": "",
            "parent_name": "",
            "members": "",
            "member_of": {},
            "email_opt_out": "",
            "invalid_email": "",
            "cases": "",
            "email": "",
            "tasks": "",
            "notes": "",
            "meetings": "",
            "calls": "",
            "emails": "",
            "documents": "",
            "bugs": "",
            "contacts": "",
            "opportunities": "",
            "project": "",
            "leads": "",
            "campaigns": "",
            "campaign_accounts": {},
            "campaign_id": "",
            "campaign_name": "",
            "prospect_lists": "",
            "aos_quotes": "",
            "aos_invoices": "",
            "aos_contracts": "",
            "accounts_aos_product_categories_1": "",
            "jjwg_maps_address_c": "",
            "jjwg_maps_geocode_status_c": "",
            "jjwg_maps_lat_c": "0.00000000",
            "jjwg_maps_lng_c": "0.00000000"
        }
    }
}

```

```json--response

HTTP/1.1 201

{
    "data": {
        "type": "Account",
        "id": "62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd",
        "attributes": {
            "name": "test",
            "date_entered": "2021-05-04T07:38:00+00:00",
            "date_modified": "2021-05-04T07:38:00+00:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "SecurityGroups": "",
            "account_type": "^Analyst^",
            "industry": "",
            "annual_revenue": "",
            "phone_fax": "",
            "billing_address_street": "",
            "billing_address_street_2": "",
            "billing_address_street_3": "",
            "billing_address_street_4": "",
            "billing_address_city": "",
            "billing_address_state": "",
            "billing_address_postalcode": "",
            "billing_address_country": "tw",
            "rating": "",
            "phone_office": "",
            "phone_alternate": "",
            "website": "",
            "ownership": "",
            "employees": "",
            "ticker_symbol": "",
            "shipping_address_street": "",
            "shipping_address_street_2": "",
            "shipping_address_street_3": "",
            "shipping_address_street_4": "",
            "shipping_address_city": "",
            "shipping_address_state": "",
            "shipping_address_postalcode": "",
            "shipping_address_country": "tw",
            "email1": "",
            "email_addresses_primary": "",
            "email_addresses": "",
            "email_addresses_non_primary": "",
            "parent_id": "",
            "sic_code": "",
            "parent_name": "",
            "members": "",
            "member_of": {},
            "email_opt_out": "",
            "invalid_email": "",
            "cases": "",
            "email": "",
            "tasks": "",
            "notes": "",
            "meetings": "",
            "calls": "",
            "emails": "",
            "documents": "",
            "bugs": "",
            "contacts": "",
            "opportunities": "",
            "project": "",
            "leads": "",
            "campaigns": "",
            "campaign_accounts": {},
            "campaign_id": "",
            "campaign_name": "",
            "prospect_lists": "",
            "aos_quotes": "",
            "aos_invoices": "",
            "aos_contracts": "",
            "accounts_aos_product_categories_1": "",
            "jjwg_maps_address_c": "",
            "jjwg_maps_geocode_status_c": "",
            "jjwg_maps_lat_c": "0.00000000",
            "jjwg_maps_lng_c": "0.00000000"
        },
        "relationships": {
            "AOS_Contracts": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/aos_contracts"
                }
            },
            "AOS_Invoices": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/aos_invoices"
                }
            },
            "AOS_Product_Categories": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/accounts_aos_product_categories_1"
                }
            },
            "AOS_Quotes": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/aos_quotes"
                }
            },
            "Accounts": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/members"
                }
            },
            "Bugs": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/bugs"
                }
            },
            "Calls": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/calls"
                }
            },
            "CampaignLog": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/campaigns"
                }
            },
            "Cases": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/cases"
                }
            },
            "Contacts": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/contacts"
                }
            },
            "EmailAddress": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/email_addresses"
                }
            },
            "Emails": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/emails"
                }
            },
            "Leads": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/leads"
                }
            },
            "Meetings": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/meetings"
                }
            },
            "Notes": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/notes"
                }
            },
            "Opportunities": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/opportunities"
                }
            },
            "Project": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/project"
                }
            },
            "ProspectLists": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/prospect_lists"
                }
            },
            "SecurityGroups": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/SecurityGroups"
                }
            },
            "Tasks": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/tasks"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/62716bfd-c6dd-e31e-2ab9-6090f9c5f2bd/relationships/modified_user_link"
                }
            }
        }
    }
}

```
Prameter                    | Description                        | Value
---                         | ---                                | ---
name                        | 客戶名稱                           |
description                 | 描述                               |
assigned_user_id            | 指派                               |
account_type                | 客戶類型(多選)                     | ^Analyst^,^Competitor^,^Customer^,^Integrator^,^Investor^,^Partner^,^Press^,^Prospect^,^Reseller^,^Supplier^,^Other^
industry                    | 產業類別                           | Apparel, Banking, Biotechnology, Chemicals, Communications, Construction, Consulting, Education, Electronics, Energy, Engineering, Entertainment, Environmental, Finance, Government, Healthcare, Hospitality, Insurance, Machinery, Manufacturing, Media, Not For Profit, Recreation, Retail, Shipping, Technology, Telecommunications, Transportation, Utilities, Other,
annual_revenue              | 年收入                             |
phone_fax                   | 傳真                               |
billing_address_street      | 付款地址 街道                      |
billing_address_city        | 付款地址 城市                      |
billing_address_state       | 付款地址 州或省                    |
billing_address_postalcode  | 付款地址 郵遞區號                  |
billing_address_country     | 付款地址 國家(ISO_3166-1_alpha-2_) | us,tw, ...
rating                      | 評價                               |
phone_office                | 辦公電話                           |
phone_alternate             | 替代電話                           |
website                     | 網站                               |
shipping_address_street     | 裝運地址 街道                      |
shipping_address_city       | 裝運地址 城市                      |
shipping_address_state      | 裝運地址 州或省                    |
shipping_address_postalcode | 裝運地址 郵遞區號                  |
shipping_address_country    | 裝運地址 國家(ISO_3166-1_alpha-2_) | us,tw, ...
campaign_id                 | 市場活動                           |


### Leads

潛在客戶 / 商業機會
可以是個人或是公司以及小型商業團體

#### Create Leads

`POST http://example.com/Api/V8/module`

```json--request

{
    "data": {
        "type": "Leads",
        "attributes": {
            "description": "Description",
            "assigned_user_id": "{{assigned_user_id}}",
            "account_id": "{{account_id}}",
            "salutation": "Mr.",
            "first_name": "Iam",
            "last_name": "Robot4",
            "title": "Mr.",
            "do_not_call": "0",
            "phone_home": "08-88888888",
            "phone_mobile": "0912345678",
            "phone_work": "07-77777777",
            "phone_other": "06-66666666",
            "phone_fax": "1234567890",
            "email1": "mark_huang1@owlting.com",
            "primary_address_street": "primary_address_street",
            "primary_address_street_2": "primary_address_street_2",
            "primary_address_street_3": "primary_address_street_3",
            "primary_address_city": "primary_address_city",
            "primary_address_state": "primary_address_state",
            "primary_address_postalcode": "primary_address_postalcode",
            "primary_address_country": "tw",
            "converted": "0",
            "refered_by": "汪東城",
            "lead_source": "Web Site",
            "lead_source_description": "lead_source_description",
            "status": "New",
            "status_description": "lead_source_description",
            "birthdate": "2020-10-06",
            "website": "http://example.com",
        }
    }
}

```

```json--response

HTTP/1.1 201

{
    "data": {
        "type": "Lead",
        "id": "4668a815-e946-dd50-7ac8-5f9927fbfd11",
        "attributes": {
            "name": "Iam Robot4",
            "date_entered": "2020-10-28T08:12:00+08:00",
            "date_modified": "2020-10-28T08:12:00+08:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "Description",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "salutation": "Mr.",
            "first_name": "Iam",
            "last_name": "Robot4",
            "full_name": "Iam Robot4",
            "title": "Mr.",
            "photo": "",
            "department": "",
            "do_not_call": "0",
            "phone_home": "08-88888888",
            "email": "",
            "phone_mobile": "0912345678",
            "phone_work": "07-77777777",
            "phone_other": "06-66666666",
            "phone_fax": "1234567890",
            "email1": "mark_huang1@owlting.com",
            "email2": "mark_huang2@owlting.com",
            "invalid_email": "0",
            "email_opt_out": "0",
            "lawful_basis": "lawful_basis",
            "date_reviewed": "",
            "lawful_basis_source": "lawful_basis_source",
            "primary_address_street": "primary_address_street\nprimary_address_street_2\nprimary_address_street_3",
            "primary_address_street_2": "",
            "primary_address_street_3": "",
            "primary_address_city": "primary_address_city",
            "primary_address_state": "primary_address_state",
            "primary_address_postalcode": "primary_address_post",
            "primary_address_country": "tw",
            "alt_address_street": "alt_address_street\nalt_address_street_2\nalt_address_street_3",
            "alt_address_street_2": "",
            "alt_address_street_3": "",
            "alt_address_city": "alt_address_city",
            "alt_address_state": "alt_address_state",
            "alt_address_postalcode": "alt_address_postalco",
            "alt_address_country": "tw",
            "assistant": "assistant",
            "assistant_phone": "assistant_phone",
            "email_addresses_primary": "",
            "email_addresses": "",
            "email_addresses_non_primary": "",
            "converted": "0",
            "refered_by": "汪東城",
            "lead_source": "Web Site",
            "lead_source_description": "lead_source_description",
            "status": "New",
            "status_description": "lead_source_description",
            "reports_to_id": "reports_to_id",
            "report_to_name": "",
            "reports_to_link": "",
            "reportees": "",
            "contacts": "",
            "account_name": "",
            "accounts": "",
            "account_description": "",
            "contact_id": "",
            "contact": "",
            "account_id": "",
            "opportunity_id": "",
            "opportunity": "",
            "opportunity_name": "",
            "opportunity_amount": "",
            "campaign_id": "",
            "campaign_name": "",
            "campaign_leads": {},
            "c_accept_status_fields": "",
            "m_accept_status_fields": "",
            "accept_status_id": "",
            "accept_status_name": "",
            "webtolead_email1": "",
            "webtolead_email2": "",
            "webtolead_email_opt_out": "",
            "webtolead_invalid_email": "",
            "birthdate": "2020-10-06",
            "portal_name": "portal_name",
            "portal_app": "portal_app",
            "website": "http://example.com",
            "tasks": "",
            "notes": "",
            "meetings": "",
            "calls": "",
            "oldmeetings": "",
            "oldcalls": "",
            "emails": "",
            "campaigns": "",
            "prospect_lists": "",
            "fp_events_leads_1": "",
            "e_invite_status_fields": "",
            "event_status_name": "",
            "event_invite_id": "",
            "e_accept_status_fields": "",
            "event_accept_status": "",
            "event_status_id": "",
            "jjwg_maps_lat_c": "0.00000000",
            "jjwg_maps_lng_c": "0.00000000",
            "jjwg_maps_geocode_status_c": "jjwg_maps_geocode_status_c",
            "jjwg_maps_address_c": "jjwg_maps_geocode_status_c"
        },
        "relationships": {
            "CampaignLog": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/campaigns"
                }
            },
            "Contacts": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/contacts"
                }
            },
            "EmailAddress": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/email_addresses"
                }
            },
            "ProspectLists": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/prospect_lists"
                }
            },
            "SecurityGroups": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/SecurityGroups"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/4668a815-e946-dd50-7ac8-5f9927fbfd11/relationships/created_by_link"
                }
            }
        }
    }
}

```

Parameter                  | Description               | Value
---------                  | -----------               | -----
description                | 描述                      |
assigned_user_id           | 指派給                    | Experience: 4e640918-9db7-2121-94b5-5eba64642e0c,
account_id                 | 客戶別（這邊帶入事業體）  | **Experience**: <br>73bad98b-40da-11eb-8665-fa163ef36d26<br>**Market:** <br>70b1530c-40da-11eb-8665-fa163ef36d26 <br>**OwlJourney:** <br>768bfdaf-40da-11eb-8665-fa163ef36d26
salutation                 | 稱呼                      | Mr.,Ms.,Mrs.,Miss,Dr.,Prof.
first_name                 | 名                        |
last_name                  | 姓                        |
title                      | 職稱                      |
do_not_call                | 不接受電訪                | 0,1
phone_home                 | 家庭電話                  | 08-88888888
phone_mobile               | 行動電話                  | 0912345678
phone_work                 | 辦公電話                  | 07-77777777
phone_other                | 傳真電話                  | 06-66666666
phone_fax                  | 傳真                      | 1234567890
email1                     | 主要聯絡                  |
email2                     | 次要聯絡                  |
invalid_email              | 無效郵件地址              | 0,1
email_opt_out              | 棄用                      | 0,1
lawful_basis               | 合法基礎                  | consent, contract, legal_obligation, protection_of_interest, public_interest, legitimate_interest, withdrawn
lawful_basis_source        | 合法基礎來源              | website, phone, given_to_user, email, third_party
date_reviewed              | 合法基礎之審核日期        |
primary_address_street     | 主要地址1                 |
primary_address_street_2   | 主要地址2                 |
primary_address_street_3   | 主要地址2                 |
primary_address_city       | 主要城市                  |
primary_address_state      | 主要州或省                |
primary_address_postalcode | 郵地區碼                  |
primary_address_country    | 國家(ISO_3166-1_alpha-2_) | us,tw, ...
converted                  | 已轉換                    | 0,1
refered_by                 | 推薦人                    |
lead_source                | 潛在客戶來源              | Cold Call, Existing Customer, Self Generated, Employee, Partner, Public Relations, Direct Mail, Conference, Trade Show, Web Site, Word of mouth, Email, Campaign, Other
lead_source_description    | 潛在客戶來源說明          | lead_source_description
status                     | 狀態                      | New, Assigned, In Process, Converted, Recycled, Dead
status_description         | 狀態描述                  |
birthdate                  | 生日                      |
website                    | 網址                      |


### Contacts

聯絡人 / 真實客戶

#### Create Contacts

`POST http://example.com/Api/V8/module`

```json--request

{
    "data": {
        "type": "Contacts",
        "attributes": {
            "description": "Description",
            "assigned_user_id": "{{assigned_user_id}}",
            "account_id": "{{account_id}}",
            "salutation": "Mr.",
            "first_name": "Iam",
            "last_name": "Robot5",
            "title": "Mr.",
            "do_not_call": "0",
            "phone_home": "08-88888888",
            "phone_mobile": "0912345678",
            "phone_work": "07-77777777",
            "phone_other": "06-66666666",
            "phone_fax": "1234567890",
            "email1": "mark_huang1@owlting.com",
            "primary_address_street": "primary_address_street",
            "primary_address_street_2": "primary_address_street_2",
            "primary_address_street_3": "primary_address_street_3",
            "primary_address_city": "primary_address_city",
            "primary_address_state": "primary_address_state",
            "primary_address_postalcode": "primary_address_postalcode",
            "primary_address_country": "tw",
            "birthdate": "2020-10-06",
            "birth_of_day_c": "birth_of_day_c",
            "birth_of_year_c": "birth_of_year_c",
            "birth_of_month_c": "birth_of_month_c",
            "membership_type_c": "normal"
        }
    }
}

```

```json--response

HTTP/1.1 201

{
    "data": {
        "type": "Contact",
        "id": "1e3924cd-4833-dfa4-b43a-5f9a336972d9",
        "attributes": {
            "name": "Iam Robot5",
            "date_entered": "2020-10-29T03:13:00+08:00",
            "date_modified": "2020-10-29T03:13:00+08:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "Description",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "salutation": "Mr.",
            "first_name": "Iam",
            "last_name": "Robot5",
            "full_name": "Iam Robot5",
            "title": "Mr.",
            "photo": "",
            "department": "",
            "do_not_call": "0",
            "phone_home": "08-88888888",
            "email": "",
            "phone_mobile": "0912345678",
            "phone_work": "07-77777777",
            "phone_other": "06-66666666",
            "phone_fax": "1234567890",
            "email1": "mark_huang1@owlting.com",
            "email2": "mark_huang2@owlting.com",
            "invalid_email": "0",
            "email_opt_out": "0",
            "lawful_basis": "lawful_basis",
            "date_reviewed": "",
            "lawful_basis_source": "lawful_basis_source",
            "primary_address_street": "primary_address_street\nprimary_address_street_2\nprimary_address_street_3",
            "primary_address_street_2": "",
            "primary_address_street_3": "",
            "primary_address_city": "primary_address_city",
            "primary_address_state": "primary_address_state",
            "primary_address_postalcode": "primary_address_post",
            "primary_address_country": "tw",
            "alt_address_street": "",
            "alt_address_street_2": "",
            "alt_address_street_3": "",
            "alt_address_city": "",
            "alt_address_state": "",
            "alt_address_postalcode": "",
            "alt_address_country": "tw",
            "assistant": "",
            "assistant_phone": "",
            "email_addresses_primary": "",
            "email_addresses": "",
            "email_addresses_non_primary": "",
            "email_and_name1": "",
            "lead_source": "",
            "account_name": "",
            "account_id": "",
            "opportunity_role_fields": "",
            "opportunity_role_id": "",
            "opportunity_role": "",
            "reports_to_id": "",
            "report_to_name": "",
            "birthdate": "2020-10-06",
            "accounts": "",
            "reports_to_link": {},
            "opportunities": "",
            "bugs": "",
            "calls": "",
            "cases": "",
            "direct_reports": "",
            "emails": "",
            "documents": "",
            "leads": "",
            "meetings": "",
            "notes": "",
            "project": "",
            "project_resource": "",
            "am_projecttemplates_resources": "",
            "am_projecttemplates_contacts_1": "",
            "tasks": "",
            "tasks_parent": "",
            "notes_parent": "",
            "user_sync": {},
            "campaign_id": "",
            "campaign_name": "",
            "campaigns": "",
            "campaign_contacts": {},
            "c_accept_status_fields": "",
            "m_accept_status_fields": "",
            "accept_status_id": "",
            "accept_status_name": "",
            "prospect_lists": "",
            "sync_contact": "",
            "fp_events_contacts": "",
            "aos_quotes": "",
            "aos_invoices": "",
            "aos_contracts": "",
            "e_invite_status_fields": "",
            "event_status_name": "",
            "event_invite_id": "",
            "e_accept_status_fields": "",
            "event_accept_status": "",
            "event_status_id": "",
            "project_contacts_1": "",
            "aop_case_updates": "",
            "joomla_account_id": "",
            "portal_account_disabled": false,
            "joomla_account_access": "",
            "portal_user_type": "Single",
            "jjwg_maps_lat_c": "0.00000000",
            "gender_c": "",
            "birth_of_day_c": "birth_of_day_c",
            "birth_of_year_c": "birth_of_year_c",
            "jjwg_maps_lng_c": "0.00000000",
            "jjwg_maps_geocode_status_c": "",
            "jjwg_maps_address_c": "",
            "birth_of_month_c": "birth_of_month_c",
            "membership_type_c": "normal"
        },
        "relationships": {
            "AM_ProjectTemplates": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/am_projecttemplates_contacts_1"
                }
            },
            "AOS_Contracts": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/aos_contracts"
                }
            },
            "AOS_Invoices": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/aos_invoices"
                }
            },
            "AOS_Quotes": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/aos_quotes"
                }
            },
            "CampaignLog": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/campaigns"
                }
            },
            "EmailAddress": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/email_addresses"
                }
            },
            "Opportunities": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/opportunities"
                }
            },
            "Project": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/project_contacts_1"
                }
            },
            "ProspectLists": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/prospect_lists"
                }
            },
            "SecurityGroups": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/SecurityGroups"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/1e3924cd-4833-dfa4-b43a-5f9a336972d9/relationships/created_by_link"
                }
            }
        }
    }
}

```

Parameter                  | Description               | Value
---------                  | -----------               | -----
description                | 描述                      | Description
assigned_user_id           | 指派給                    | Experience: 4e640918-9db7-2121-94b5-5eba64642e0c
account_id                 | 客戶別（這邊帶入事業體）  | **Experience**: <br>73bad98b-40da-11eb-8665-fa163ef36d26<br>**Market:** <br>70b1530c-40da-11eb-8665-fa163ef36d26 <br>**OwlJourney:** <br>768bfdaf-40da-11eb-8665-fa163ef36d26
salutation                 | 稱呼                      | Mr.,Ms.,Mrs.,Miss,Dr.,Prof.
first_name                 | 名                        |
last_name                  | 姓                        |
title                      | 職稱                      |
do_not_call                | 不接受電訪                | 0,1
phone_home                 | 家庭電話                  | 08-88888888
phone_mobile               | 行動電話                  | 0912345678
phone_work                 | 辦公電話                  | 07-77777777
phone_other                | 傳真電話                  | 06-66666666
phone_fax                  | 傳真                      | 1234567890
email1                     | 主要聯絡                  |
email2                     | 次要聯絡                  |
invalid_email              | 無效郵件地址              | 0,1
email_opt_out              | 棄用                      | 0,1
lawful_basis               | 合法基礎                  | consent, contract, legal_obligation, protection_of_interest, public_interest, legitimate_interest, withdrawn
lawful_basis_source        | 合法基礎來源              | website, phone, given_to_user, email, third_party
date_reviewed              | 合法基礎之審核日期        |
primary_address_street     | 主要地址1                 |
primary_address_street_2   | 主要地址2                 |
primary_address_street_3   | 主要地址3                 |
primary_address_city       | 主要城市                  |
primary_address_state      | 主要州或省                |
primary_address_postalcode | 郵地區碼                  |
primary_address_country    | 國家(ISO_3166-1_alpha-2_) | us,tw, ...
lead_source                | 潛在客戶來源              | Cold Call, Existing Customer, Self Generated, Employee, Partner, Public Relations, Direct Mail, Conference, Trade Show, Web Site, Word of mouth, Email, Campaign, Other
lead_source_description    | 潛在客戶來源說明          | lead_source_description
birthdate                  | 生日                      |
birth_of_day_c             | 日                        |
birth_of_year_c            | 年                        |
birth_of_month_c           | 月                        |
membership_type_c          | 會員身份狀態              | normal, premium



### Currencies

貨幣

<aside class="info"><strong>Important</strong>: 預設幣別(TWD) 無法透過api 查詢 直接帶入-99</aside>

Parameter       | Description | Value
---------       | ----------- | -----
name            | 貨幣名稱    | EUR
symbol          | 貨幣符號    |
iso4217         | ISO4217編碼 | https://www.iso.org/iso-4217-currency-codes.html
conversion_rate | 匯率        | 跟預設幣別 (TWD) 的比率
status          | 狀態        | Active, Inactive

`GET http://example.com/Api/V8/module/Currencies?page[size]=10&page[number]=1`

```json--response
{
    "meta": {
        "total-pages": 1,
        "records-on-this-page": 1
    },
    "data": [
        {
            "type": "Currency",
            "id": "6ccfc88a-598b-898a-91f5-5f7ed4511cc2",
            "attributes": {
                "name": "EUR",
                "symbol": "EUR",
                "iso4217": "",
                "conversion_rate": "1.2",
                "status": "Active",
                "deleted": "0",
                "date_entered": "2020-10-08T08:58:00+08:00",
                "date_modified": "2020-10-08T08:58:00+08:00",
                "created_by": "1",
                "hide": "",
                "unhide": ""
            },
            "relationships": []
        }
    ],
    "links": {
        "first": null,
        "prev": null,
        "next": null,
        "last": null
    }
}
```

### Products

產品

#### Create Products

Parameter               | Description       | Value
---------               | -----------       | -----
name                    | 產品名稱          |
description             | 描述              |
assigned_user_id        | 負責人            |
part_number             | 部件編碼          | M01040500000282
type                    | 產品類型          | Good,Service
cost                    | 成本              |
cost_usdollar           | 成本 ( 預設貨幣 ) |
currency_id             | 貨幣              |
price                   | 價格              |
price_usdollar          | 價格 ( 預設貨幣 ) |
url                     | 超連結            |
contact_id              | 聯絡人            |
account_c               | 客戶名稱          |
account_id_c            | 客戶編號          |
advance_booking_days_c  | 提前預定天數      | 0
latitude_c              | 經度              | 24.99931400
longitude_c             | 緯度              | 121.51631800
aos_product_category_id | 產品類別          |
room_source_c           | 房源（journey 用）|


<aside class="info"><strong>Info</strong>: Journey 特殊料號</aside>

| id                                   | name          | number                         |
| ---                                  | ---           | ---                            |
| db576c01-8b7a-3169-4d41-60780e186c76 | 尾差金額料號  | J00000000000000000000000000004 |
| a80d3168-7b8a-d7ec-e701-60780f94a6aa | 代收房費-小孩 | J00000000000000000000000000003 |
| b9f90b33-d6e0-9249-5578-60780f5dd917 | 代收房費-大人 | J00000000000000000000000000002 |
| 63e51ab7-619b-4fe4-c3e8-60780e042f79 | 服務收入      | J00000000000000000000000000001 |


`POST http://example.com/Api/V8/module`

```json--request
{
    "data": {
        "type": "AOS_Products",
        "attributes": {
            "name": "MIS 【預購商品 佑爾康金貝親 HappyFamily有機蔬果牙餅 蘋果口味】用最天",
            "description": "MIS 【預購商品 佑爾康金貝親 HappyFamily有機蔬果牙餅 蘋果口味】用最天",
            "part_number": "MISM01040500000282",
            "type": "Good",
            "cost": "180.000000",
            "cost_usdollar": "180.000000",
            "currency_id": "{{currency_id}}",
            "price": "180.000000",
            "price_usdollar": "180.00",
            "url": "",
            "contact_id": "",
            "aos_product_category_id": "{{product_category_id}}",
            "room_source_c": "owljourney"
        }
    }
}

```

```json--response
{
    "data": [
        {
            "type": "AOS_Product_Categories",
            "id": "173f2e49-ebc0-ac85-f383-5f7d82c7b1fb",
            "attributes": {
                "name": "E",
                "date_entered": "2020-10-07T08:54:00+08:00",
                "date_modified": "2020-10-07T08:54:00+08:00",
                "modified_user_id": "4e640918-9db7-2121-94b5-5eba64642e0c",
                "modified_by_name": "Experience",
                "created_by": "4e640918-9db7-2121-94b5-5eba64642e0c",
                "created_by_name": "Experience",
                "description": "Experiences體驗大類",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "is_parent": "1",
                "aos_products": "",
                "sub_categories": "",
                "parent_category": {},
                "parent_category_name": "",
                "parent_category_id": ""
            },
            "relationships": {
                "AOS_Product_Categories": {
                    "links": {
                        "related": "V8/module/AOS_Product_Categories/173f2e49-ebc0-ac85-f383-5f7d82c7b1fb/relationships/parent_category"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/AOS_Product_Categories/173f2e49-ebc0-ac85-f383-5f7d82c7b1fb/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/AOS_Product_Categories/173f2e49-ebc0-ac85-f383-5f7d82c7b1fb/relationships/created_by_link"
                    }
                }
            }
        }
    ],
}
```

### Products Categories

#### 產品類別

Parameter          | Description | Value
---------          | ----------- | -----
name               | 名稱        |
description        | 描述        |
assigned_user_id   | 負責人      | 1
is_parent          | 是父類別    | 0,1
parent_category_id | 父類別      |


### Invoice

發票(收據) / 銷售紀錄

稅務算方式為外加稅

Parameter                    | Description               | Value
---------                    | -----------               | -----
name                         | 職稱                      |
description                  | 描述                      |
assigned_user_id             | 負責人                    |
billing_account_id           | 客戶                      |
billing_contact_id           | 聯絡人                    |
billing_address_street       | 街道                      |
billing_address_city         | 城市                      |
billing_address_state        | 州或省                    |
billing_address_country      | 國家(ISO_3166-1_alpha-2_) | us,tw, ...
shipping_address_street      | 街道                      |
shipping_address_city        | 城市                      |
shipping_address_state       | 州或省                    |
shipping_address_postalcode  | 郵遞區號                  |
shipping_address_country     | 國家(ISO_3166-1_alpha-2_) | us,tw, ...
total_amt                    | 訂單總計                  | 6971 (item_groups 的 amount)
total_amt_usdollar           | 訂單總計（預設貨幣）      | 6971
subtotal_amount              | 訂單小計                  | 6891 ( total_amt - discount_amount )
subtotal_amount_usdollar     | 訂單小計（預設貨幣）      | 6891
discount_amount              | 訂單折扣總計              | -80
discount_amount_usdollar     | 訂單折扣總計（預設貨幣）  | -80
tax_amount                   | 訂單稅金總計 (訂單貨幣)   | 349.55 ( item_groups 的tax_amount + shipping_tax_amt )
tax_amount_usdollar          | 訂單稅金總計（預設貨幣）  | 349.55
shipping_amount              | 訂單貨運                  | 100
shipping_amount_usdollar     | 訂單貨運（預設貨幣）      | 100
shipping_tax                 | 訂單貨運稅 (百分之幾)     | 5.0
shipping_tax_amt             | 訂單貨運稅                | 5 ( shipping_amount * shipping_tax / 100 )
shipping_tax_amt_usdollar    | 訂單貨運稅（預設貨幣）    | 5
total_amount                 | 訂單含稅總計              | 7340.55 ( subtotal_amount + tax_amount + shipping_amount)
total_amount_usdollar        | 訂單含稅總計（預設貨幣）  | 7340.55
currency_id                  | 訂單貨幣                  | -99
quote_number                 | 報價編號                  |
quote_date                   | 報價日期                  |
invoice_date                 | 發票日期                  |
receipt_number_c             | 發票號碼                  |
order_type_c                 | 訂單類別                  |
payment_method_c             | 付款方式                  | 'apple_pay', 'line_pay', 'wechat_pay',<br> 'cash_on_delivery', 'ali_pay', 'credit_card',<br> 'atm', 'intella_pay', 'experiences',<br> 'paynow_creadit_card', 'stripe_credit_card', 'google_pay',<br> 'paynow_credit_card3ds',
due_date                     | 到期時間                  |
status                       | 狀態                      | Paid,PendingPaymentConfirmation,Unpaid,<br> Cancelled,Rescheduling,Returning,Returned
subtotal_tax_amount          | 小計＋稅金                | 0
subtotal_tax_amount_usdollar | 小計＋稅金（預設貨幣）    | 0
billing_address_postalcode   | 郵遞區號                  |
potr_c                       | 付款編號                  |
number_of_nights_c           | 入住夜數 (journey)        |
number_of_rooms_c            | 房間數 (journey)          |


```json--request
{
    "data": {
        "type": "AOS_Invoices",
        "attributes": {
            "name": "MIS004",
            "description": "",
            "deleted": "0",
            "billing_account_id": "670f411d-7f4f-abc5-d253-5eac39e93e09",
            "billing_account": "EC_Market",
            "billing_contact_id": "",
            "billing_contact": "",
            "billing_address_street": "",
            "billing_address_city": "",
            "billing_address_state": "",
            "billing_address_postalcode": "",
            "billing_address_country": "",
            "shipping_address_street": "",
            "shipping_address_city": "",
            "shipping_address_state": "",
            "shipping_address_postalcode": "",
            "shipping_address_country": "",
            "number": "",
            "total_amt": "399.000000",
            "total_amt_usdollar": "399.000000",
            "subtotal_amount": "378.000000",
            "subtotal_amount_usdollar": "378.000000",
            "discount_amount": "-21.000000",
            "discount_amount_usdollar": "-21.000000",
            "tax_amount": "0.000000",
            "tax_amount_usdollar": "0.000000",
            "shipping_amount": "0.000000",
            "shipping_amount_usdollar": "0.000000",
            "shipping_tax": "0",
            "shipping_tax_amt": "0.000000",
            "shipping_tax_amt_usdollar": "0.000000",
            "total_amount": "378.000000",
            "total_amount_usdollar": "378.000000",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2",
            "quote_number": "",
            "quote_date": "",
            "invoice_date": "202-02-03",
            "order_type_c": "zero-order",
            "due_date": "",
            "status": "Paid",
            "template_ddown_c": "",
            "subtotal_tax_amount": "",
            "subtotal_tax_amount_usdollar": "0.000000",
            "potr_c": ""
            "number_of_nights_c": "1",
            "number_of_rooms_c": "2"
        }
    }
}
```

```json--response
{
    "data": {
        "type": "AOS_Invoices",
        "id": "b4534cda-6fe8-2926-47b4-5fa3d3146c98",
        "attributes": {
            "name": "MIS004",
            "date_entered": "2020-11-05T10:26:00+08:00",
            "date_modified": "2020-11-05T10:26:00+08:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "billing_account_id": "",
            "billing_account": "",
            "billing_contact_id": "",
            "billing_contact": "",
            "billing_address_street": "",
            "billing_address_city": "",
            "billing_address_state": "",
            "billing_address_postalcode": "",
            "billing_address_country": "",
            "shipping_address_street": "",
            "shipping_address_city": "",
            "shipping_address_state": "",
            "shipping_address_postalcode": "",
            "shipping_address_country": "",
            "number": "18985",
            "line_items": "",
            "total_amt": "399.000000",
            "total_amt_usdollar": "399.000000",
            "subtotal_amount": "378.000000",
            "subtotal_amount_usdollar": "378.000000",
            "discount_amount": "-21.000000",
            "discount_amount_usdollar": "-21.000000",
            "tax_amount": "0.000000",
            "tax_amount_usdollar": "0.000000",
            "shipping_amount": "0.000000",
            "shipping_amount_usdollar": "0.000000",
            "shipping_tax": "0",
            "shipping_tax_amt": "0.000000",
            "shipping_tax_amt_usdollar": "0.000000",
            "total_amount": "378.000000",
            "total_amount_usdollar": "378.000000",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2",
            "quote_number": "0",
            "quote_date": "",
            "invoice_date": "",
            "due_date": "",
            "status": "Paid",
            "template_ddown_c": "",
            "subtotal_tax_amount": "0.000000",
            "subtotal_tax_amount_usdollar": "0.000000",
            "accounts": "",
            "contacts": "",
            "aos_quotes_aos_invoices": "",
            "aos_products_quotes": "",
            "aos_line_item_groups": "",
            "aos_invoices_aos_invoices_1": "",
            "invoice_datetime_c": ""
        },
        "relationships": {
            "AOS_Invoices": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/aos_invoices_aos_invoices_1"
                }
            },
            "AOS_Line_Item_Groups": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/aos_line_item_groups"
                }
            },
            "AOS_Products_Quotes": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/aos_products_quotes"
                }
            },
            "AOS_Quotes": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/aos_quotes_aos_invoices"
                }
            },
            "Accounts": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/accounts"
                }
            },
            "Contacts": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/contacts"
                }
            },
            "SecurityGroups": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/SecurityGroups"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/b4534cda-6fe8-2926-47b4-5fa3d3146c98/relationships/created_by_link"
                }
            }
        }
    }
}
```

### Item Groups

小計群組

Parameter                    | Description          | Value | Example
---------                    | -----------          | ----- | -------
name                         | 名稱                 |       |
description                  | 描述                 |       |
assigned_user_id             | 負責人               |       |
total_amt                    | 總計                 |       | 5971
total_amt_usdollar           | 總計（預設貨幣）     |       | 5971
discount_amount              | 折扣總計             |       | -30
discount_amount_usdollar     | 折扣總計（預設貨幣） |       | -30
subtotal_amount              | 小計總計             |       | total_amt - discount_amount = 5941
subtotal_amount_usdollar     | 小計總計             |       | 5941
tax_amount                   | 稅額                 |       | total_amt * 0.05 = 297.05
tax_amount_usdollar          | 稅額                 |       | 297.05
subtotal_tax_amount          | 小計                 |       | 0.000000
subtotal_tax_amount_usdollar | 小計（預設貨幣）     |       | 0.000000
total_amount                 | 總計                 |       | 6238.05
total_amount_usdollar        | 總計（預設貨幣）     |       | 6238.05
parent_type                  | 類型                 |       | AOS_Invoices


```json--request
{
    "data": {
        "type": "AOS_Line_Item_Groups",
        "attributes": {
            "name": "name",
            "description": "description",
            "total_amt": "180.000000",
            "total_amt_usdollar": "180.000000",
            "discount_amount": "0.000000",
            "discount_amount_usdollar": "0.000000",
            "subtotal_amount": "180.000000",
            "subtotal_amount_usdollar": "180.000000",
            "tax_amount": "0.000000",
            "tax_amount_usdollar": "0.000000",
            "subtotal_tax_amount": "0.000000",
            "subtotal_tax_amount_usdollar": "0.000000",
            "total_amount": "180.000000",
            "total_amount_usdollar": "180.000000",
            "parent_type": "AOS_Invoices",
            "parent_id": "{{invoice_id}}",
            "number": "1",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2"
        }
    }
}
```

```json--response
{
    "data": {
        "type": "AOS_Line_Item_Groups",
        "id": "1f58e96f-f3aa-0937-f19d-5fa3d39107ce",
        "attributes": {
            "name": "name",
            "date_entered": "2020-11-05T10:27:00+08:00",
            "date_modified": "2020-11-05T10:27:00+08:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "description",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "c56be602-4a6b-269c-e734-5eaeb97af366",
            "assigned_user_name": "ec_market",
            "assigned_user_link": "",
            "total_amt": "180.000000",
            "total_amt_usdollar": "180.000000",
            "discount_amount": "0.000000",
            "discount_amount_usdollar": "0.000000",
            "subtotal_amount": "180.000000",
            "subtotal_amount_usdollar": "180.000000",
            "tax_amount": "0.000000",
            "tax_amount_usdollar": "0.000000",
            "subtotal_tax_amount": "0.000000",
            "subtotal_tax_amount_usdollar": "0.000000",
            "total_amount": "180.000000",
            "total_amount_usdollar": "180.000000",
            "parent_name": "MIS004",
            "parent_type": "AOS_Invoices",
            "parent_id": "b4534cda-6fe8-2926-47b4-5fa3d3146c98",
            "number": "1",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2",
            "aos_products_quotes": ""
        },
        "relationships": {
            "AOS_Products_Quotes": {
                "links": {
                    "related": "V8/module/1f58e96f-f3aa-0937-f19d-5fa3d39107ce/relationships/aos_products_quotes"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/1f58e96f-f3aa-0937-f19d-5fa3d39107ce/relationships/created_by_link"
                }
            }
        }
    }
}
```

### Items

小計群組裡面的商品

Parameter                        | Description             | Value             | Example
---------                        | -----------             | -----             | -------
name                             | 名稱                    |                   |
description                      | 描述                    |                   |
assigned_user_id                 | 負責人                  |                   |
currency_id                      | 幣別                    | 預設貨幣(-99)     | -99
part_number                      | 部件編號                |                   | J_725_3314
item_description                 | 商品描述                |                   | ""
number                           | 順序                    |                   | 1
product_qty                      | 商品數量                |                   | 2
product_cost_price               | 商品成本                |                   | 2700
product_cost_price_usdollar      | 商品成本 (預設幣別)     |                   | 2700
product_list_price               | 商品價格                |                   | 2700
product_list_price_usdollar      | 商品價格 (預設幣別)     |                   | 2700
product_discount                 | 折扣                    |                   | 10
product_discount_usdollar        | 折扣 (預設幣別)         |                   | 10
product_discount_amount          | 折扣總計                |                   | ""
product_discount_amount_usdollar | 折扣總計 (預設幣別)     |                   | ""
discount                         | 折扣類型                | Amount, Percetage | Amount
product_unit_price               | 產品單位價格            |                   | 2690
product_unit_price_usdollar      | 產品單位價格 (預設幣別) |                   | 2690
departure_datetime_c             | 出團日期                |                   | 2020-01-01
vat_amt                          | 含稅價                  |                   | 269
vat_amt_usdollar                 | 含稅價 (預設幣別)       |                   | 269
product_total_price              | 商品含稅總額            |                   | 5380
product_total_price_usdollar     | 商品含稅總額 (預設幣別) |                   | 5380
vat                              | 稅率                    |                   | 5.0
parent_id                        | 發票編號                |                   | {{invoice_id}}
product_id                       | 產品編號                |                   | {{product_id}}
group_id                         | 小計編號（產品組）      |                   | {{item_group_id}
date_start_c                     | 開始時間 (journey)      |                   | Y-m-d H:i:s
date_end_c                       | 結束時間 (journey)      |                   | Y-m-d H:i:s

```json--request
{
    "data": {
        "type": "AOS_Products_Quotes",
        "attributes": {
            "name": "name",
            "description": "description",
            "deleted": "0",
            "assigned_user_id": "c56be602-4a6b-269c-e734-5eaeb97af366",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2",
            "part_number": "M01990100000001",
            "item_description": "",
            "number": "1",
            "product_qty": "1.0000",
            "product_cost_price": "180.000000",
            "product_cost_price_usdollar": "180.000000",
            "product_list_price": "180.000000",
            "product_list_price_usdollar": "180.000000",
            "product_discount": "0.000000",
            "product_discount_usdollar": "0.000000",
            "product_discount_amount": "",
            "product_discount_amount_usdollar": "",
            "discount": "Percentage",
            "product_unit_price": "0.000000",
            "product_unit_price_usdollar": "0.000000",
            "vat_amt": "0.000000",
            "vat_amt_usdollar": "0.000000",
            "product_total_price": "180.000000",
            "product_total_price_usdollar": "180.000000",
            "date_start_c": "2021-06-01 17:00:00",
            "date_end_c" : "2021-06-02 09:00:00",
            "vat": "0",
            "parent_name": "OD2020040900050",
            "parent_type": "AOS_Invoices",
            "parent_id": "{{invoice_id}}",
            "product_id": "{{product_id}}",
            "group_id": "{{item_group_id}}"
        }
    }
}
```

```json--response
{
    "data": {
        "type": "AOS_Products_Quotes",
        "attributes": {
            "name": "name",
            "description": "description",
            "deleted": "0",
            "assigned_user_id": "c56be602-4a6b-269c-e734-5eaeb97af366",
            "currency_id": "47009c9c-6151-33e1-49a1-5ea287700de2",
            "part_number": "M01990100000001",
            "item_description": "",
            "number": "1",
            "product_qty": "1.0000",
            "product_cost_price": "180.000000",
            "product_cost_price_usdollar": "180.000000",
            "product_list_price": "180.000000",
            "product_list_price_usdollar": "180.000000",
            "product_discount": "0.000000",
            "product_discount_usdollar": "0.000000",
            "product_discount_amount": "",
            "product_discount_amount_usdollar": "",
            "discount": "Percentage",
            "product_unit_price": "0.000000",
            "product_unit_price_usdollar": "0.000000",
            "vat_amt": "0.000000",
            "vat_amt_usdollar": "0.000000",
            "product_total_price": "180.000000",
            "product_total_price_usdollar": "180.000000",
            "vat": "0",
            "parent_name": "OD2020040900050",
            "parent_type": "AOS_Invoices",
            "parent_id": "{{invoice_id}}",
            "product_id": "{{product_id}}",
            "group_id": "{{item_group_id}}"
        }
    }
}
```

### Promotions

促銷相關訊息

Parameter        | Description  | Value | Example
---------        | -----------  | ----- | -------
name             | 促銷名稱     |       |
description      | 描述         |       |
assigned_user_id | 負責人       |       |
code             | 促銷編碼     |       |
priority         | 優先權       | 0~99  |
exclusive        | 獨一         | 0,1   |
usage_limit      | 使用次數限制 | 0     |
used             | 已使用次數   |       |
coupon_based     | 需配合折扣碼 | 0,1   |
date_start       | 開始日期     |       |
date_end         | 結束日期     |       |

`GET http://example.com/Api/V8/module/OWL_Promotions?page[size]=10&page[number]=1&sort=name`

```json--response
{
    "meta": {
        "total-pages": 1,
        "records-on-this-page": 2
    },
    "data": [
        {
            "type": "OWL_Promotions",
            "id": "95ccec35-d944-3df1-edd1-5faba28ab21f",
            "attributes": {
                "name": "Market Premium 500",
                "date_entered": "2020-11-11T08:35:00+00:00",
                "date_modified": "2020-11-11T09:52:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "單筆消費折扣後滿 500 元即享免運費",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "code": "Market Premium 500",
                "priority": "0",
                "exclusive": "0",
                "usage_limit": "0",
                "used": "0",
                "coupon_based": "0",
                "date_start": "2020-11-11T04:00:00+00:00",
                "date_end": "2020-11-11T05:00:00+00:00",
                "owl_promotionactions_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotionrules_owl_promotions": ""
            },
            "relationships": {
                "OWL_PromotionActions": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/95ccec35-d944-3df1-edd1-5faba28ab21f/relationships/owl_promotionactions_owl_promotions"
                    }
                },
                "OWL_PromotionCoupons": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/95ccec35-d944-3df1-edd1-5faba28ab21f/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "OWL_PromotionRules": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/95ccec35-d944-3df1-edd1-5faba28ab21f/relationships/owl_promotionrules_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/95ccec35-d944-3df1-edd1-5faba28ab21f/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/95ccec35-d944-3df1-edd1-5faba28ab21f/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_Promotions",
            "id": "cbfd0ade-3c89-5737-0933-5faba09842b2",
            "attributes": {
                "name": "Market Premium 9 percetage discount",
                "date_entered": "2020-11-11T08:27:00+00:00",
                "date_modified": "2020-11-11T08:33:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "code": "Market Premium",
                "priority": "0",
                "exclusive": "0",
                "usage_limit": "0",
                "used": "0",
                "coupon_based": "0",
                "date_start": "2020-11-11T04:00:00+00:00",
                "date_end": "2020-11-11T05:00:00+00:00",
                "owl_promotionactions_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotionrules_owl_promotions": ""
            },
            "relationships": {
                "OWL_PromotionActions": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/cbfd0ade-3c89-5737-0933-5faba09842b2/relationships/owl_promotionactions_owl_promotions"
                    }
                },
                "OWL_PromotionCoupons": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/cbfd0ade-3c89-5737-0933-5faba09842b2/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "OWL_PromotionRules": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/cbfd0ade-3c89-5737-0933-5faba09842b2/relationships/owl_promotionrules_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/cbfd0ade-3c89-5737-0933-5faba09842b2/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_Promotions/cbfd0ade-3c89-5737-0933-5faba09842b2/relationships/created_by_link"
                    }
                }
            }
        }
    ],
    "links": {
        "first": null,
        "prev": null,
        "next": null,
        "last": null
    }
}
```

### Promotions Rules

促銷條件

Parameter     | Description | Value 
---------     | ----------- | ----- 
name          | 規則名稱    |
description   | 描述        |
type          | 規則類別    | cart_quantity, <br> item_total, <br> has_taxon, <br> must_taxon, <br> has_category, <br> must_category, <br> total_of_items_from_taxon, <br> total_of_items_from_category, <br> nth_order, <br> contains_product, <br> contains_role, <br> except_product
configuration | 設定        | 

#### type 與 configuration 公式

type                         | description                 | php metadata                                   | configuration
---                          | ---                         | ---                                            | ---
cart_quantity                | 這邊是 item 總數量          | ['count' => $count]                            | {"count":100}
item_total                   | 這邊是 item 總金額          | ['amount' => $amount]                          | {"amount":1000}
has_taxon                    | 至少有一個活動類別的商品    | ['taxons' => $taxons]                          | {"taxons":["boys","girls"]}
must_taxon                   | 全部都必須為活動類別的商品  | ['taxons' => $taxons]                          | {"taxons":["boys","girls"]}
has_category                 | 至少有一個為產品類別的商品  | ['categories' => $categories]                  | {"categories":["boys","girls"]}
must_category                | 全部都必須為產品類別的商品  | ['categories' => $categories]                  | {"categories":["boys","girls"]}
total_of_items_from_taxon    | 符合銷售類別 的 item 總金額 | ['taxon' => $taxonCode, 'amount' => $amount]   | {"taxon":"boys","amount":1000}
total_of_items_from_category | 符合產品類別的 item 總金額  | ['category' => $category, 'amount' => $amount] | {"category":"boys","amount":1000}
nth_order                    | 使用者購買的第幾筆訂單      | ['nth' => $nth]                                | {"nth":3}
contains_product             | 產品編號為                  | ['products_codes' => $productsCodes]           | {"products_codes":["boys","girls"]}
contains_role                | 角色身份為                  | ['roles_codes' => $rolesCodes]                 | {"roles_codes":["support","admin"]}
except_product               | 產品編號不為                | ['products_codes' => $productsCodes]           | {"products_codes":["E123","E456"]}

<aside class="info"><strong>Important</strong>: 儲存格式為 json string </aside>

`GET http://example.com/Api/V8/module/OWL_PromotionRules?page[size]=10&page[number]=1&sort=name`

```json--response
{
    "meta": {
        "total-pages": 1,
        "records-on-this-page": 2
    },
    "data": [
        {
            "type": "OWL_PromotionRules",
            "id": "573c8396-553a-7c5d-01e0-60e65fffc31a",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T02:15:00+00:00",
                "date_modified": "2021-07-08T02:17:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "configuration": "{&quot;amount&quot;:1000}",
                "type": "item_total",
                "owl_promotionrules_owl_promotions": "",
                "owl_promotionrules_owl_promotions_name": "2020年末Sale100",
                "owl_promotionrules_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/573c8396-553a-7c5d-01e0-60e65fffc31a/relationships/owl_promotionrules_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/573c8396-553a-7c5d-01e0-60e65fffc31a/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/573c8396-553a-7c5d-01e0-60e65fffc31a/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_PromotionRules",
            "id": "9111a188-0030-7130-2eda-60e65f7a970b",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T02:14:00+00:00",
                "date_modified": "2021-07-08T02:18:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "configuration": "{&quot;count&quot;:100}",
                "type": "cart_quantity",
                "owl_promotionrules_owl_promotions": "",
                "owl_promotionrules_owl_promotions_name": "2020年末Sale100",
                "owl_promotionrules_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/9111a188-0030-7130-2eda-60e65f7a970b/relationships/owl_promotionrules_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/9111a188-0030-7130-2eda-60e65f7a970b/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionRules/9111a188-0030-7130-2eda-60e65f7a970b/relationships/created_by_link"
                    }
                }
            }
        }
    ],
    "links": {
        "first": null,
        "prev": null,
        "next": null,
        "last": null
    }
}
```

### Promotions Actions

促銷折扣

Parameter     | Description | Value | description
---------     | ----------- | ----- | -------
name          | 規則名稱    |
description   | 描述        |
type          | 規則類別    | cart_quantity, <br> item_total, <br> has_taxon, <br> must_taxon, <br> has_category, <br> must_category, <br> total_of_items_from_taxon, <br> total_of_items_from_category, <br> nth_order, <br> contains_product, <br> contains_role, <br> except_product
configuration | 設定        |

#### type 與 configuration 公式

type                               | description                | php metadata                  | Value
---                                | ---                        | ---                           | ---
order_fixed_discount               | 固定折扣                   | ['amount' => $amount]         | {"amount":-100}
unit_fixed_discount                | 每單位折扣                 | ['amount' => $amount]         | {"amount":-100}
order_percentage_discount          | 每筆訂單固定則扣           | ['percentage' => $percentage] | {"percentage":0.9}
unit_percentage_discount           | 單位固定則扣               | ['percentage' => $percentage] | {"percentage":0.9}
shipping_percentage_discount       | 運費百分比折扣             | ['percentage' => $percentage] | {"percentage":0.9}
owlting_coin_fixed_from_total      | 每多少金額轉換固定奧丁幣   | ['amount' => $amount]         | {"amount":100}
owlting_coin_percentage_from_total | 每多少百分比金額轉換奧丁幣 | ['percentage' => $percentage] | {"percentage":0.01}

`GET http://example.com/Api/V8/module/OWL_PromotionActions?page[size]=10&page[number]=1&sort=name`

```json--response
{
    "meta": {
        "total-pages": 1,
        "records-on-this-page": 1
    },
    "data": [
        {
            "type": "OWL_PromotionActions",
            "id": "7e9af65e-01a5-dc31-63a9-60e6621ba0b0",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T02:26:00+00:00",
                "date_modified": "2021-07-08T02:26:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "configuration": "{&quot;amount&quot;:-100}",
                "type": "order_fixed_discount",
                "owl_promotionactions_owl_promotions": "",
                "owl_promotionactions_owl_promotions_name": "2020年末Sale100",
                "owl_promotionactions_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionActions/7e9af65e-01a5-dc31-63a9-60e6621ba0b0/relationships/owl_promotionactions_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionActions/7e9af65e-01a5-dc31-63a9-60e6621ba0b0/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionActions/7e9af65e-01a5-dc31-63a9-60e6621ba0b0/relationships/created_by_link"
                    }
                }
            }
        }
    ],
    "links": {
        "first": null,
        "prev": null,
        "next": null,
        "last": null
    }
}
```

### Promotions Coupons

促銷相關訊息

Parameter                      | Description          | Value    | Example
---------                      | -----------          | -----    | -------
name                           | 折扣碼名稱           |          |
description                    | 描述                 |          |
code                           | 折扣碼               |          |
usage_limit                    | 使用次數限制         |          |
reusable_from_cancelled_orders | 可不可以重複使用     | 0,1      |
used                           | 已使用次數           | 0        |
expires_at                     | 過期日期             | datetime |
per_customer_usage_limit       | 每個使用者使用的次數 | 1        |

`GET http://example.com/Api/V8/module/OWL_PromotionCoupons?page[size]=10&page[number]=1&sort=name`

```json--response
{
    "meta": {
        "total-pages": 1,
        "records-on-this-page": 5
    },
    "data": [
        {
            "type": "OWL_PromotionCoupons",
            "id": "33005b3d-3393-128a-d037-60e6a7bc5703",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T07:20:00+00:00",
                "date_modified": "2021-07-08T07:20:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "code": "coupon1104",
                "usage_limit": "1",
                "reusable_from_cancelled_orders": "0",
                "used": "0",
                "expires_at": "2021-07-08T04:00:00+00:00",
                "per_customer_usage_limit": "1",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions_name": "2020年末Sale100",
                "owl_promotioncoupons_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/33005b3d-3393-128a-d037-60e6a7bc5703/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/33005b3d-3393-128a-d037-60e6a7bc5703/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/33005b3d-3393-128a-d037-60e6a7bc5703/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_PromotionCoupons",
            "id": "9ba594b8-96b2-e662-683c-60e6a68cbbb4",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T07:18:00+00:00",
                "date_modified": "2021-07-08T07:18:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "code": "coupon1101",
                "usage_limit": "1",
                "reusable_from_cancelled_orders": "0",
                "used": "0",
                "expires_at": "2021-07-08T04:00:00+00:00",
                "per_customer_usage_limit": "1",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions_name": "2020年末Sale100",
                "owl_promotioncoupons_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/9ba594b8-96b2-e662-683c-60e6a68cbbb4/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/9ba594b8-96b2-e662-683c-60e6a68cbbb4/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/9ba594b8-96b2-e662-683c-60e6a68cbbb4/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_PromotionCoupons",
            "id": "c2b8e837-a668-3439-6e40-60e6a6901b1b",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T07:19:00+00:00",
                "date_modified": "2021-07-08T07:19:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "code": "coupon1102",
                "usage_limit": "1",
                "reusable_from_cancelled_orders": "0",
                "used": "0",
                "expires_at": "2021-07-08T04:00:00+00:00",
                "per_customer_usage_limit": "1",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions_name": "2020年末Sale100",
                "owl_promotioncoupons_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c2b8e837-a668-3439-6e40-60e6a6901b1b/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c2b8e837-a668-3439-6e40-60e6a6901b1b/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c2b8e837-a668-3439-6e40-60e6a6901b1b/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_PromotionCoupons",
            "id": "d630cde3-66fe-dd0b-19f4-60e6a78dee5f",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T07:20:00+00:00",
                "date_modified": "2021-07-08T07:20:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "code": "coupon1105",
                "usage_limit": "1",
                "reusable_from_cancelled_orders": "0",
                "used": "0",
                "expires_at": "2021-07-08T04:00:00+00:00",
                "per_customer_usage_limit": "1",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions_name": "2020年末Sale100",
                "owl_promotioncoupons_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/d630cde3-66fe-dd0b-19f4-60e6a78dee5f/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/d630cde3-66fe-dd0b-19f4-60e6a78dee5f/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/d630cde3-66fe-dd0b-19f4-60e6a78dee5f/relationships/created_by_link"
                    }
                }
            }
        },
        {
            "type": "OWL_PromotionCoupons",
            "id": "c92617af-c937-59aa-7599-60e6a7cca402",
            "attributes": {
                "name": "2020年末Sale100",
                "date_entered": "2021-07-08T07:19:00+00:00",
                "date_modified": "2021-07-08T07:19:00+00:00",
                "modified_user_id": "1",
                "modified_by_name": "Administrator",
                "created_by": "1",
                "created_by_name": "Administrator",
                "description": "",
                "deleted": "0",
                "created_by_link": "",
                "modified_user_link": "",
                "assigned_user_id": "1",
                "assigned_user_name": "Administrator",
                "assigned_user_link": "",
                "SecurityGroups": "",
                "code": "coupon1103",
                "usage_limit": "1",
                "reusable_from_cancelled_orders": "0",
                "used": "0",
                "expires_at": "2021-07-08T04:00:00+00:00",
                "per_customer_usage_limit": "1",
                "owl_promotioncoupons_owl_promotions": "",
                "owl_promotioncoupons_owl_promotions_name": "2020年末Sale100",
                "owl_promotioncoupons_owl_promotionsowl_promotions_ida": "3d13a002-9741-e33e-805f-60d445b13572"
            },
            "relationships": {
                "OWL_Promotions": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c92617af-c937-59aa-7599-60e6a7cca402/relationships/owl_promotioncoupons_owl_promotions"
                    }
                },
                "SecurityGroups": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c92617af-c937-59aa-7599-60e6a7cca402/relationships/SecurityGroups"
                    }
                },
                "Users": {
                    "links": {
                        "related": "V8/module/OWL_PromotionCoupons/c92617af-c937-59aa-7599-60e6a7cca402/relationships/created_by_link"
                    }
                }
            }
        }
    ],
    "links": {
        "first": null,
        "prev": null,
        "next": null,
        "last": null
    }
}
```
### Map - Markers

Maps locations

Parameter        | Description               | Value              | Example
---------        | -----------               | -----              | -------
name             | 標記名稱                  |                    |
marker_type_c    | 標記類別                  | origin,destination |
description      | 描述                      |                    |
assigned_user_id | 負責人                    |                    |
city             | 城市                      |                    |
state            | 州或省                    |                    |
country          | 國家(ISO_3166-1_alpha-2_) |                    | us,tw, ...
jjwg_maps_lat    | 經度                      |                    | 113.727
jjwg_maps_lng    | 緯度                      |                    | 34.773
marker_image     | 標注類型                  |                    | accident, administration, agriculture, aircraft_small, airplane_tourism, airport, amphitheater, apartment, aquarium, arch, atm, audio, bank, bank_euro, bank_pound, bar, beach, beautiful, bicycle_parking, big_city, bridge, bridge_modern, bus, cable_car, car, car_rental, carrepair, castle, cathedral, chapel, church, city_square, cluster, cluster_2, cluster_3, cluster_4, cluster_5, coffee, community_centre, company, conference, construction, convenience, court, cruise, currency_exchange, customs, cycling, dam, dentist, deptartment_store, disability, disabled_parking, doctor, dog_leash, down, down_left, down_right, down_then_left, down_then_right, drugs, elevator, embassy, expert, factory, falling_rocks, fast_food, festival, fjord, forest, fountain, friday, garden, gas_station, geyser, gifts, gourmet, grocery, hairsalon, helicopter, highway, historical_quarter, home, hospital, hostel, hotel, hotel_1_star, hotel_2_stars, hotel_3_stars, hotel_4_stars, hotel_5_stars, info, justice, lake, laundromat, left, left_then_down, left_then_up, library, lighthouse, liquor, lock, main_road, massage, mobile_phone_tower, modern_tower, monastery, monday, monument, mosque, motorcycle, museum, music_live, oil_pump_jack, pagoda, palace, panoramic, park, park_and_ride, parking, photo, picnic, places_unvisited, places_visited, playground, police, port, postal, power_line_pole, power_plant, power_substation, public_art, rain, real_estate, regroup, resort, restaurant, restaurant_african, restaurant_barbecue, restaurant_buffet, restaurant_chinese, restaurant_fish, restaurant_fish_chips, restaurant_gourmet, restaurant_greek, restaurant_indian, restaurant_italian, restaurant_japanese, restaurant_kebab, restaurant_korean, restaurant_mediterranean, restaurant_mexican, restaurant_romantic, restaurant_thai, restaurant_turkish, right, right_then_down, right_then_up, saturday, school, shopping_mall, shore, sight, small_city, snow, spaceport, speed_100, speed_110, speed_120, speed_130, speed_20, speed_30, speed_40, speed_50, speed_60, speed_70, speed_80, speed_90, speed_hump, stadium, statue, steam_train, stop, stoplight, subway, sun, sunday, supermarket, synagogue, tapas, taxi, taxiway, teahouse, telephone, temple_hindu, terrace, text, theater, theme_park, thursday, toilets, toll_station, tower, traffic_enforcement_camera, train, tram, truck, tuesday, tunnel, turn_left, turn_right, university, up, up_left, up_right, up_then_left, up_then_right, vespa, video, villa, water, waterfall, watermill, waterpark, watertower, wednesday, wifi, wind_turbine, windmill, winery, work_office, world_heritage_site, zoo,


```json--request
{
    "data": {
        "type": "jjwg_Markers",
        "attributes": {
            "name": "Mis Marker",
            "marker_type_c": "origin",
            "description": "體驗一日遊",
            "assigned_user_id": "123",
            "city": "",
            "state": "",
            "country": "tw",
            "jjwg_maps_lat": "123",
            "jjwg_maps_lng": "123",
            "marker_image": ""
        }
    }
}
```

```json--response
{
    "data": {
        "type": "jjwg_Markers",
        "id": "c88dd3c5-5093-714b-584a-6098b8762c66",
        "attributes": {
            "name": "Mis Marker",
            "date_entered": "2021-05-10T04:36:00+00:00",
            "date_modified": "2021-05-10T04:36:00+00:00",
            "modified_user_id": "1",
            "modified_by_name": "Administrator",
            "created_by": "1",
            "created_by_name": "Administrator",
            "description": "體驗一日遊",
            "deleted": "0",
            "created_by_link": "",
            "modified_user_link": "",
            "assigned_user_id": "123",
            "assigned_user_name": "",
            "assigned_user_link": "",
            "SecurityGroups": "",
            "city": " ",
            "state": " ",
            "country": "tw",
            "jjwg_maps_lat": "100.00000000",
            "jjwg_maps_lng": "123.00000000",
            "marker_image": "",
            "jjwg_maps_jjwg_markers": "",
            "aos_products_jjwg_markers_1": "",
            "aos_products_jjwg_markers_1_name": "",
            "aos_products_jjwg_markers_1aos_products_ida": ""
        },
        "relationships": {
            "AOS_Products": {
                "links": {
                    "related": "V8/module/c88dd3c5-5093-714b-584a-6098b8762c66/relationships/aos_products_jjwg_markers_1"
                }
            },
            "SecurityGroups": {
                "links": {
                    "related": "V8/module/c88dd3c5-5093-714b-584a-6098b8762c66/relationships/SecurityGroups"
                }
            },
            "Users": {
                "links": {
                    "related": "V8/module/c88dd3c5-5093-714b-584a-6098b8762c66/relationships/created_by_link"
                }
            }
        }
    }
}
```
