# taxonomy-for-data-as-art-material
A concise taxonomy for describing data used as an art material

Released under the Attribution 4.0 International Creative Commons license

This is version 2.0 Your comments, critiques, suggestions are very welcome.

# Summary 

* Of living: Biological; Environmental
* Of non-living: Object
* Of social context: Commercial; Personal; Social; State
* Of licence: Closed; Open; Shared
* Of time/space: Geospatial; Live; Real-time; Static; Temporal
* Of type: Anecdata; Causal; Generated; Metadata; Processed; Retrieved; Streamed
* Of disclosure: Anonymised; Identifiable; Unknown

# Term Definitions

Living: Biological
* Data whose origin is directly linked to something that is alive. Data that occurs without conscious origin (i.e not from a human typing). Often from sensors. Examples: a) species migration reported by a sensor; b) quantified self data (for instance, output from a heart-rate monitor); c) a bird-call.

Living: Environmental 
* Data whose origin is directly linked to the natural world. Often from sensors. Examples: a) ocean temperature, b) solar storm activity, c) seed bank information.

Non-Living: Object
* Data whose origin is a physical object or device. Object data is often generated for machine to machine communication, however, the Internet of Things will see a greater machine to (human) consumer communication. Examples: a) a fridge's energy use; b) a CCTV camera; c) a smart watch.

Social Content: Commercial
* Data produced by or about a corporate entity. Examples: a) 10 years of financial information about a company; b) the expiry date on a chocolate bar.

Social Content: Personal
* Data produced by or about an individual. Certain types will have restricted access, and some legal and technical protections. Other will be accessible by some, if not all, of the general public. Examples: a) Google's search analysis profile of a non-anonymised individual's interests; b) International travel logs held at border controls; c) a recording of a private telephone conversation; d) family photos publicly tagged on Flickr; e) your social network feed.

Social Content: Social
* Data produced by or about a social group or society. Examples; a) global number of births each day; b) voting preference in a London borough; c) immigration figures.

Social Content: State
* Data produced by or about a government or ruling authority. Examples: a) the economy of the eurozone; b) legislation documents

Licence: Closed
* Closed data is generally only accessible to people within an organisation or to certain individuals. Examples: a) company personnel files; b) national security documents

Licence: Open 
* Open data can be accessed, used, and shared by anyone. Examples: a) publicly funded research data; b) earthquake monitoring data

Licence: Shared 
* Shared data is data available to a specific group of people for a specific purpose. Examples: a) the electoral register; b) anonymized supermarket shopping patterns

Time/Space: Geospatial
* Data describing, is relevant to, or is derived from a space or geographic area. Examples: a) GPS coordinates from a cross-country walk; b) the number of people visiting the Tate Modern art gallery; c) the area of a baseball pitch; d) longitude and latitude.

Time/Space: Live
* Data which is, or was, captured in real-time. The recording does not necessarily get played-back at the same rate, or in the same moment. Examples: a) a football match on TV; b) animal tracking data

Time/Space: Real-time
* Data that is created, captured and disseminated in an immediate time-frame relative to the context of its use; it changes over time. Examples: a) smart-meter reporting electricity usage every 30 seconds (real-time data acquisition with a relevant-time display); b) feeds from sensors such as a webcam on a birds nest, a GPS location of a mobile phone, or a humidity reading in an gallery space.

Time/Space: Static
* Data in which the items do not change once created, dataset grows over time. Includes historical datasets and archive indexes. Examples: a) historical global population size; b) the sound archive at the British Library.

Time/Space: Temporal
* Data which is time-based in its nature, relevant to a specific time, or which may only exist for a short time period (transient). Examples: a) the value of a grain of rice over time; b) your date of birth; c) the radio signals received from an exploding star.

Type: Anecdata
* Anecdotal information gathered and then presented as fact. Anecdata is often not precisely measurable, has no reliable provenance, is hard to compare, and /or cannot be unproven by the scientific method. Examples: a) a collection of comments on a product website; b) proverbs such as ``Never look a gift horse in the mouth''.

Type: Causal
* Data in which it is (or is made) obvious to the observer what its origin is. Example: a vocal recording

Type: Generated
* Data created by a software program. Examples: a) algorithmic music; b) cellular automaton; c) a model of a galaxy exploding.

Type: Metadata
* Data about data. Data which describes information about other data. Examples: a) the number of rows in a database; b) the time and date a phone call was made.

Type: Processed
* Data which has been calculated, altered or processed in some way (most often by an algorithm). Examples: a) a sonification of stock market figures; b) aggregated statistics; c) a colourful digital photograph reduced to black and white.

Type: Retrieved
* Data made available on request by machine or user. Examples: a) compilation of weather data from the past 24 hours as a single CSV file b) availability status of a library book.

Type: Streamed
* The technical means of delivering real-time data as a contiguous stream. The primary use-cases are where there is no requirement for data storage, or that the data-sets involved are too large to be manipulated in any other manner (the entire Twitter back catalogue). Examples: a) real-time audio and video from a carnival procession; b) on-demand replay of a film from 1960; c) music playing from a digital radio.

Of Disclosure: Anonymised
* Data that has had any identifiable in- formation about a person, animal, or thing removed. Examples: a) CCTV camera footage containing people which have been blurred or obfuscated; b) all bicycle hire users across a city with user IDs and names removed.

Disclosure: Identifiable
* Data in which the direct source within it (person, animal, or thing) can be identified. Examples: a) a Facebook data export including friend names; b) a set of mobile phone numbers with owner address details.

Of Disclosure: Unknown
* Data which contains information about a person, animal, or thing but in which it is not clear if it is adequately anonymised. Examples: a) a live Twitter feed containing some geolocated photos of people and animals; b) a sound recording from a public space that includes ambient conversation.


# Notes
Additional Dataset Parameters
* There are aspects of data that are useful to explore in the process of understanding datasets which are not included in the vocabulary. These tend toward more technical descriptions and are used by archivists and preservation experts. The W3C Data on the Web Best Practices Use Cases & Requirements Note, http://www.w3.org/TR/dwbp-ucr/ (accessed 20 June 2015), recommends these elements are used for defining data: domains, obligation/motivation, usage, quality, lineage, size, type/format, rate of change, data lifespan, potential audience. We recommend considering the following, particularly for retrieval, maintenance, and archival purposes of the artwork.
* Accessibility & how and by whom can the dataset be accessed and used (licensing rights, availability, database rights), and is this reliable and future-proof?
* Accuracy: how exact are the individual data points. e.g. If it is real-time data is there latency to acknowledge
* Context: does this dataset provide meaning through its relationships to other datasets (for comparative interest, for ratification)?
* Dimensionality & how many dimensions are represented (e.g. a point against time, a number of parameters)?
* Format: what is the structure and format (technical data structure and/or data definition, distribution)?
* Provenance: scientific datasets should be reproducible, others should be collated from, or by, reliable sources. Any bias should be declared or detected.
* Relevancy: are the data points relevant to each other, to someone or something (e.g. a machine)?
* Size: The order of magnitude of the number of data points, the sample size. Examples: 1, or 1 million). Often imprecisely referred to as large (big) data or small data.
* Utility: does the data have potential to provide utility by providing new content or insight, is this important to the work?
