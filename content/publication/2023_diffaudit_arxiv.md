---
title: "DiffAudit: Auditing Privacy Practices of Online Services for Children and Adolescents"
authors:
- Olivia Figueira
- Rahmadi Trimananda
- Athina Markopoulou
- Scott Jordan
date: "2023-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

#abstract: Children's and adolescents' online data privacy are regulated by laws such as the Children's Online Privacy Protection Act (COPPA) and the California Consumer Privacy Act (CCPA). Online services that are directed towards general audiences, including children, adolescents, and adults alike, must comply with these laws. In this paper, first, we develop DiffAudit, a platform-agnostic privacy auditing methodology for online services that are directed towards general audiences. DiffAudit performs differential analysis of network traffic and compares the data collection and sharing practices of the service under audit for children, adolescents, and adults as well as audits the services based on COPPA and CCPA for children and adolescents. A novel component of our methodology is our data type classification method that utilizes GPT-4 to classify data extracted from the network traffic packets, and we present a data type ontology based on COPPA and CCPA definitions of personal information and identifiers used for the classification labels. Second, we apply DiffAudit to a set of popular general audience services, on both their mobile and website platforms, and we present the results. Through network traffic analysis, we observe a rich set of data collection and sharing behaviors extracted from over 440K outgoing requests, with 3,968 unique data types extracted from the packets, resulting in 5,508 unique data flows (i.e., data type category and destination pair). Our data type classification approach achieves 87% sample accuracy with 70% coverage of our dataset, compared to 31% accuracy achieved by the best-performing alternative. We find that none of the services we studied significantly alter their data processing according to user age as we expect, and all of the services engage in behaviors that raise concern with respect to COPPA and/or CCPA, such as collecting personal information and identifiers about children and adolescent users and sharing such data with advertising and tracking services.

# Summary. An optional shortened abstract.
#summary: ArXiv Preprint

featured: false

links:
url_pdf: https://arxiv.org/abs/2406.06473
---
