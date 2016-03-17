# JSON-LD TAGS

Sections of JSON Tags

## NewsArticle
    mainEntityOfPage
    headline
    keywords
    image (ImageObject)
    dateCreated
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
    accountablePerson (person)
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
    Location (Place)
    foundingDate
    numberOfEmployees
    award
    legalName
    sameAs (list of URLS)
    memberOf (trust project for example etc. as ProgramMembership)
## Person
    givenName
    familyName
    jobTitle
    email (?)
    memberOf (ProgramMembership - "codice di condotta" affiliation)
    award
    sameAs (list of URLS)
    Location (Place.)
## ProgramMembership (reference of memberOf)
    hostingOrganization (Organization)
    membershipNumber
    programName
    image (ImageObject)
    url (URL)
