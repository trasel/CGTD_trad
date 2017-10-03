**Corrida da contagem**

Em 2004, o governo da Florida criou uma lista dos condenados aos quais não era permitido votar. Eles fizeram isso cruzando os nomes de um banco de dados de registros criminais e um banco de dados de eleitores registrados. Os tribunais ordenaram que a lista fosse divulgada ao público e, logo após, o *Sarasota Herald Tribune* descobriu que quase não havia hispânicos na lista.[10](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

Isso parecia impossível. Os hispânicos compunham 17% da população, mas apenas um décimo de 1% da lista; havia apenas 61 indivíduos hispânicos na lista de 47.763 nomes. Na época, os eleitores hispânicos da Flórida eram na maioria cubanos que apoiavam o Partido Republicano. Se eles não estivessem na lista, poderiam votar. Houve acusações de fraude por motivos políticos.

More digging revealed that this was not actually a political maneuver but a data problem. In the state's voter database, Hispanic is a "race." In the criminal history database, Hispanic is an "ethnicity." The same information was conceived in two different ways, so it was recorded in two different fields in two different systems. To prevent false matches based on name alone, the government had chosen to match on name, date of birth, and "race" but not "ethnicity." Thus, Hispanic felons could never match Hispanic voters.[11](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

Which database schema is correct? Is Hispanic an ethnicity or a race? This sounds like a cultural, social, or even philosophical question, but in this context it's really a question about the process of counting. After all, these databases are concrete objects, created by humans. At some point there was a decision that each person was, or was not, Hispanic, and this value was recorded in either the "race" or "ethnicity" column.

How do you assign a racial category to each person, or even decide what those categories should be? This is a problem that the U.S. Census has solved, for better or worse, for over 200 years.

Article I, Section 2 of the 1787 Constitution established the census and divided people into three categories: "free persons"; "Indians not taxed"; and "other persons," which really meant "slaves." Although aligned with race, these were also political categories because the census was created to apportion representatives and taxes between the states. Indians counted for neither representation nor taxes, while slaves were only counted as three-fifths of a person. This was the compromise between the slave and non-slave states that created the country. It seems insane now, but that's the history, and a reminder that the census is not an "objective" count but a bureaucratic process that generates data for specific purposes. Asking *why* the data was collected does not answer how it was collected, but it's often a big hint.

Over the next century it became possible for a person to be counted in many more different ways. The category of "free colored person" appeared in 1820. No one was interracial, according to the data, until the 1850 census added the category of "mulatto." The 1890 census expanded into ethnicity and finer shades of black when it asked "whether white, black, mulatto, quadroon, octoroon, Chinese, Japanese, or Indian."

Of course you could see people of all these types on city streets by then---but not in the official statistics until these additions. Categories were being added to better describe a reality that could already be perceived by other means. Which doesn't make the categories reality. There were huge numbers of people who didn't fit into any of these categories, like the Irish, who suffered intense racism in nineteenth-century America.

But a list of races doesn't tell us how a person's race was actually determined. In practice, a census enumerator visited each home and checked a box. For decades, enumerators were told to count someone as black if there was any degree of black ancestry, echoing the "one drop rule" of the Jim Crow era. Here's how race was supposed to be quantified for the 1940 census:

![](https://cjrarchive.org/img/posts/dj02.png)

*Instructions for quantifying race and sex on the 1940 census*.[12](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

It's not clear how census-takers were supposed to determine someone's ancestry going back generations, or how they applied this rule in practice, or if they even read the instructions---meaning that we don't know quite how to interpret the racial categories of the early twentieth-century census. If the collection method is obscure, so is the data.

Then things changed. In the mid-twentieth century there was a huge shift in the way race was counted, but not because of social or philosophical ideals. Instead the motive was statistical accuracy.

Close analysis of the 1940 census data suggested that the results were low by 3.6 percent, meaning millions of people had not been counted. The census was supposed to be a simple count, but the massive undercount proved that counting was anything but simple. And some people were more undercounted than others: 13 percent of non-"white" people were missing from the census results.

There was clearly a racial bias in the census-taking process. It was soon discovered that census enumerators were having difficulty identifying American Indians in urban areas where they were mixed in with majority white populations. This proved that looking at someone didn't always provide an accurate impression of their race. To address this, the 1960 census used a different approach: People were simply asked what race they were.

If self-identification seems the obvious way to determine race, that's because we now understand race as an entanglement of identity, culture, and biology, as much social as genetic. But that is a late twentieth-century understanding. The census officials of the 1950s do not seem to have understood race this way; they simply wanted a more accurate count and took for granted that a person knows their own race.

There is something about self-identification that feels like a step forward in codifying race, a better way of making it visible in the aggregate. it's a more dignified approach. But it has its own serious limitations. it's not the data you need if you want to study race-linked genetic diseases or how people treat strangers differently based on skin color. We can think of race in many different ways, but the available data has no obligation to match our conceptions. If you want to know what the data really measures, the only thing that matters is how it was collected. Hence, the census up to 1950 counts something different than the census from 1960 onward, even though both call it "race." How is it different? That depends on the question you wish to ask of the data.

Meanwhile, Hispanics had begun to make up a significant fraction of the U.S. population, and "Hispanic" finally appeared on census forms in 1970. Before that the census said nothing about how many Hispanic people lived in the country, where they lived, their incomes, or any of the other variables now routinely collected.

Things changed again in 1977 with a new set of federal government guidelines on the collection of race data, the infamous "Directive 15" from the Office of Management and Budget. This recommended dividing race into four categories: "American Indian or Alaska Native," "Asian or Pacific Islander," "Black," and "White." It also said "it is preferable to collect data on race and ethnicity separately" and defined ethnicity as "Hispanic origin" or "not of Hispanic origin." The logic here is that Hispanics can be any race, such as Afro-Cubans. Which is great, except that about a third of all Hispanic people consider "Hispanic" to be a race, or at least they check "other race" on their census forms and write in "Hispanic" or "Mexican" or "Latina."[13](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations)

This is how Florida's criminal history database came to code Hispanics differently than Florida's voter registration database. The database of felons coded race according to federal standards, so race could only be white, black, Asian, American Indian, or unknown. Hispanic was coded as an ethnicity, in a different field. Meanwhile, the voter registration database coded Hispanic as a race. A simple comparison on the "race" field failed, because race is not a simple thing to quantify.

If the federal racial categorization system feels a bit arbitrary, that's because it is. Even its creators knew not to take it too seriously, writing, "These classifications should not be interpreted as being scientific or anthropological in nature."[14](https://www.cjr.org/tow_center_reports/the_curious_journalists_guide_to_data.php#citations) Nonetheless, all of the federal government's race data includes these four master categories to this day. But many agencies also collect more detailed information on racial sub-categories. The census has long included a growing list of Asian races, and you've been able to write in any race you want since 1910.

The last major change to the race questions on the census came in 2000. Now you're allowed to check multiple races on the census form, in addition to several possible choices for Hispanic ethnicity. The 2010 form looked like this:

![](https://cjrarchive.org/img/posts/dj03.png)

On the 2010 census, 2.9 percent of the population identified as two or more races. This is nine million people who are expressing a type of racial identity which was invisible before we decided to count it.
