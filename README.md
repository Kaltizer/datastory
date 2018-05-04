# Decolonize Brooklyn Museum: Uncovering Legacies of Colonialism in Big Data 

## 
For this exercise, I analyzed twitter data that reveals fascinating intersections between gentrification and museum practice. I used a fairly simple search, #decolonizebrooklynmuseum since:2018-04-17 until:2018-05-01, to explore the response of anti-gentrification groups to the Brooklyn Museum’s hiring of a white woman as their curator of African art. Protesting both the museum’s hiring practices and its role in promoting gentrification in the area, Decolonize Brooklyn organized a protest at the museum, after which the group moved to the nearby site of a high-rise construction site that threatens the Brooklyn Botanic Garden.
  
I used twarc to grab over 600 #decolonizebrooklynmuseum tweets. I placed this data into Google Sheets and began to ask a series of questions: where are these twitter users based? Are the users with the largest platforms community stakeholders? Or are they activists based elsewhere? Are museum professionals responding to the conversation using this hashtag? Experimenting with several different ways of assessing and visualizing the location data associated with the hashtag, I realized that although the user-entered location information suggested that users were primarily in the east coast and probably tweeting from urban areas, I could not be confident in the data. After experimenting with charts and pivot tables, I realized that a chart showing the timezone of the tweet was likely the most reliable indicator of a tweeter’s location. This chart shows that, indeed, the majority of twitter users tweeting about the protest were either in New York City or urban east coast areas. To further assess the demographics of the hashtag users, it would also be interesting to be able to use an add-on that could analyze word patterns in the user descriptions and tweets themselves to discover the overlapping interest groups supporting @DecolonizeBrooklyn. By analyzing the location and affiliations of the users of #decolonizebrooklynmuseum, one could begin to theorize reasons for the presence or absence of museum professionals in the conversation. 

To me, this data is fascinating because of the stories that it points to but cannot tell. I am interested in the ways in which digitized collections data from collections management systems makes visible erased histories of oppression and exploitation. Museum collections databases could be scraped and analyzed in the way that twarc grabs data from twitter. A fascinating study would be a comparison of twitter data alongside museum collections data; this comparison could visualize the underrepresented communities alongside the acquisition information of heritage objects  in order to make underrepresented voices of the past and present heard. 

Although conversations about the ethics of possessing and analyzing twitter users’ data--as well as museum collections data--need to continue, it is my opinion at this stage that accessibility to museum collections databases, as well as public twitter information, can tell stories that other types of institutions cannot. Museum data stories are often stories of oppression, erasure, and exploitation; telling those stories reveals that colonization is evident not only in historic museum collections but also in the communities in which the museums function. Thus, the Decolonize Brooklyn protest connects to many different types of data stories: the twitter data story surrounding the event, and the data story of the museum collections themselves. This twitter conversation is important because it makes visible the legacy of colonization that built museum collections, a legacy that continues today in the form of gentrification. 


#### Appendix: Decolonize Brooklyn Museum Flyer
1. “Territorial acknowledgement of Indigenous land occupied by this building and giving material effect to such acknowledgement in curatorial practices, programming, exhibitions and day-to-day operations.”

2. “Deep diversification of of curatorial staff and executive leadership whereby the lived experience of oppressions–including patriarchy, white supremacy and poverty–are valued and factored in.”

3. “A decolonial inventory of colonial-era objects of both African and Indigenous people with a view to settling the long-pursued claims of reparations and repatriation.”

4. “An upgrade of working conditions and pay of ground staff–disproportionately people of color–in security, food service and janitorial divisions.”

5. “Replacement of board president David Berliner and other trustees who are real estate tycoons with a broad cross-section of artists and community organizers.”

6. “De-gentrification initiative to examine and mitigate museum’s role in boosting land value and rents in the borough”
“Institutional commitment to address the boycott, divestment and sanctions movement in recognition of Brooklynites’ role in the settler movement in Palestine.”

-- http://www.nicholasmirzoeff.com/bio/decolonize-the-brooklyn-museum-a-non-response-is-not-an-option/

#### Examples of Links

A link to my [data](https://github.com/Kaltizer/datastory/blob/master/data/tweets2.csv)

![chart](https://github.com/umd-mith/datastory/raw/master/images/chart.png)

