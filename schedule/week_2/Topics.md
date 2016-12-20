# Topics

## # Week 2: Philcamp: Digital philology, creating a digital edition

### Day 1: Modeling

On the first day of Week 2 we emphasize three foundational aspects of digital textual scholarship: _text as graph_ (TAG), _theory of edition_, and the _Gothenburg model_ of textual variance (GM). This day will also cover developing project specifications and defining goals and non-goals to avoid _scope-creep_.




### Day 2: Transcription, tokenization, and normalization

Manuscript materials must be digitized as character data for subsequent computational processing as text. Transcription, tokenization, and normalization are foundational issues in philology independently of computation, but the digital environment entails additional assumptions and consequences. On Day 2 the instructors will first introduce computer character set conventions (plain vs fancy text, character vs glyph, Unicode, etc.). They will then guide the participants through the division of continuous text into smaller units for subsequent comparison (tokenization), and discuss strategies for letting the research goals of the project guide decisions about normalization. This portion of the Institute will also explore contextual normalization, that is, ways of exploiting textual distinctions for some purposes while ignoring them for others.

### Day 3: Collation

On Day 3 the instructors will explore the alignment stage of GM, or collation, through a hands-on introduction to using the open-source CollateX framework to align the participants’ own documents. This introduction will explore collation as a philological process (determining what to align with what), as a matter of data modeling (employing the notion of the _variant graph_ [Schmidt 2009]), and as an engineering challenge (negotiating the ambiguities and complexities raised by repetition, transposition, order effects, exact vs fuzzy matching, etc.).


The analysis stage is the researcher’s opportunity to interact with the automated alignment. This day will explore ways to build on top of XML structures (for example, using ranges or graphs) to represent properties that are difficult to express and process efficiently solely within the XML tree model. Day 4 will draw attention to layers of annotation (base, linguistic, named entity, etc.), examining how annotation layers interact within an edition. Participants will learn about customized annotation (e.g., through XPath), about natural language processing tools (Stanford, NLTK) that can be recruited to support linguistic annotation, and about the integration of those formerly stand-alone, plaintext applications into an XML environment (such as the recent incorporation of the Stanford NLP tools into the eXist-db XML database by one of the Institute instructors).

Beginning in Week 2, Day 4 and continuing through Week 3, Day 1, the Institute will welcome Mike Kestemont, a founding member of the Computational Stylistics Group, whose expertise in stylometry during the transition from Week 2 to Week 3 will supplement the digital edition expertise of the core instructors. On Week 2, Day 4 participants will be introduced to annotation-related prerequisites for the statistical exploration and analysis of textual information.

### Day 5: Query and exploration

Week 2, Day 5 develops a query functionality that lets the user express research questions in a way that addresses relevant annotation layers and retrieves information in a variety of formats (e.g., table, tree, graphic visualization). To the user this may look like an XML database, but underneath it can integrate tree, range, and graph modeling. Day 5 will include a discussion of textual queries and the retrieval of textual results, on the one hand, and statistical queries and the graphic visualization of their results, on the other.

## References

Schmidt, Desmond. 2009. “Merging multi-version texts: a generic solution to the overlap problem.” Presented at Balisage: the markup conference 2009, Montréal, Canada, August 11–14, 2009. In _Proceedings of Balisage: the markup conference 2009._ Balisage series on markup technologies, 3. doi:10.4242/BalisageVol3.Schmidt01.

Sels, Lara and David J. Birnbaum 2015. “Editing the _Bdinski sbornik_ as a multilayered reality.” _Агиославика. Проблеми и подходи в изследването на Станиславовия чети-миней: доклади от едноименната конференция - 21 май 2013 г._ (_Hagioslavica. Issues and approaches in the study of the_ Stanislav Reading Menaion_: presentations from the conference of May 21, 2013.), ed. Diana Atanasova. Sofia: Kliment Oxridski University, pp. 184–99.