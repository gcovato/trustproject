# JSON-LD TAGS

Sections of JSON Tags

## NewsArticle
    mainEntityOfPage
    headline
    keywords
    image (ImageObject)
    dateCreated
    dateModified
    datePublished
    dateModified
    printPage - for aticles published on newspaper
    printSection - for aticles published on newspaper
    articleSection
    PublishingPrinciples (url)
    license (url)
    copyrightYear
    copyrightHolder (Organization)
    publisher (Organization)
    author (person)
    contributor (person)
    citation (CreativeWork)
    commentCount
## MediaObject
    +CreativeWorks
    associatedArticle
## Organization
    name
    logo (ImageObject)
    globalLocationNumber
    foundingDate
    numberOfEmployees
    award
    legalName
    memberOf (trust project for example etc. as ProgramMembership)
## Person
    givenName
    familyName
    jobTitle
    email (?)
    memberOf (ProgramMembership - "codice di condotta" affiliation)
    award
    globalLocationNumber (to set when the article was written.)
## ProgramMembership (reference of memberOf)
    hostingOrganization (Organization)
    membershipNumber
    programName
    image (ImageObject)
    url (URL)
