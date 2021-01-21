# Anchor-Therapy-LLC
Note - This project was done as a part of the Practicum in Analysis course in BIA at Stevens Institute of Technology.

Anchor Therapy is a mental health counseling center in downtown Hoboken, NJ operated by two therapists. Their mission is to help you, or your teen, feel relief from whatever stress one’s dealing with. Our focus is on devising the right marketing strategy for Anchor Therapy to deliver optimal solutions to maximize public interest that translates into increasing her client base. 

Initial days were utilised to understand the clent base in and around the city of Hoboken and Jersey City to an extent. This followed by extensive research on clinics like Starr Therapy, LLC and Lukin Center, who offered therapy sessions in Hoboken itself. We studied various features like demograph, cost, time, etc. The approach we took was to enrich UX by developing a Chatbot for Anchor's website and target the right audience by understanding Twitter posts in Hoboken and Jersey City. 

The Chatbot makes use of a small mental health dataset found on Kaggle. It consists of 2 variables - "Questions" and "Answers", with around 50 inatances. The process followed for implementation included Data Processing and Data Modeling. For modeling we trained a LSTM-based Seq2Seq model to predict decoder outputs, given encoder outputs and decoder inputs. We also trained a Bidirectional LSTM model with an attention layer and then compared the validation accuracy scores of the two models.

Coming now to the Twitter Scraper. We obtained the consumer and access kets from the Twitter API. Next step was to search for varying forms of common words associated with mental illness like "depression", "sad", "anxious", etc. The tweets were filtered according to the area using longitude, latitude and the radius. And finally we used loops to obtain the desired tweets with the user names.

In conclusion, we would like to say that we successfully devised a mechanism based on web-scraping framework to extract the usernames of people who might be affected directly or indirectly by depression. We also modeled a successfully running chatbot that needs more data for it to be trained with and which Anchor Therapy can have on their website as it would help enhance their customer engagement and be available 24x7 to prospective clients. 
