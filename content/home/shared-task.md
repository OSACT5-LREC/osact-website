---
widget: blank
headless: true

# ... Put Your Section Options Here (title etc.) ...
title: Shared Task
subtitle:
weight: 30  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
---
<div class="container">
        <div class="row">
          <div class="col-lg-8 mx-auto">
            <p class="lead"><font size = "4">
            <h> <font size = "6"> Quran QA Shared Task </font></h> <br>
            Reading comprehension (RC) task, viewed as a type of questions-answering (QA) tasks, is perceived as the ideal method to evaluate language understanding by computer systems. Given a passage of text, a machine reading comprehension system is required to answer a set of questions over the given passage. We propose a shared task of Arabic Reading Comprehension over the Holy Qur’an, aiming to trigger state-of-the-art reading comprehension research on a book that is sacredly held by more than 1.8 billion people across the world. <br>
The Holy Qur’an is composed of 114 chapters (Suras) and 6,236 verses that comprise more than 80k words in Classical Arabic. The participating systems are expected to provide answers to questions on given passages (sets of consecutive verses) from the Holy Qur’an, where the answers are spans of text extracted from the given passages. Our dataset for the shared task (developed based on the AyaTEC dataset) is composed of 1,348 QA tuples of passage-question-answer triplets for 169 different questions. The dataset adopts the same format of the SQuAD v1.1 dataset. A question might have more than one answer in the passage; therefore, the system is expected to extract all of them and return a ranked list of answer spans. To evaluate the system performance, multiple evaluation measures, that adopt exact and partial matching of spans, will be used.
<br><br>
<h><font size = "6">Fine-grained detection of hate speech on Arabic Twitter Shared Task </font></h> <br>
Detecting offensive language and hate speech has gained an increasing interest from researchers in NLP and computational social sciences communities in the past few years. For example, at the ACL 2021 main conference, there wereare 3 papers about offensive language, and 10 papers about hate speech <a href = "https://2021.aclweb.org/program/accept/">(https://2021.aclweb.org/program/accept/).</a>  Additionally, there was a dedicated workshop on online abuse and harm with a shared task on hateful memes <a href = "https://www.workshopononlineabuse.com/home#h.czplpodomjyq">(https://www.workshopononlineabuse.com/home#h.czplpodomjyq).</a> Detecting offensive language and hate speech is very important for online safety, content moderation, etc. Studies show that the presence of hate speech may be connected to hate crimes (Hate Speech Watch, 2014). <br> <br>
            Given the success of the shared task on Arabic offensive language detection at OSACT 2020 <a href = "https://edinburghnlp.inf.ed.ac.uk/workshops/OSACT4/">(https://edinburghnlp.inf.ed.ac.uk/workshops/OSACT4/),</a> we decided to continue our effort to enhance detection of offensive language and hate speech on Arabic Twitter. We share with the research community the largest annotated Arabic tweets that don’t have bias towards specific topics, genres or dialects. Each tweet is judged by 3 annotators using crowdsourcing for offensiveness. Offensive tweets were classified to one of hate speech types: Gender, Race, Ideology, Social Class, Religion, and Disability. Also, annotators judged whether a tweet has vulgar language or violence. <br><br>
            Hate speech is defined as any kind of offensive language (insults, slurs, threats, encouraging violence, etc.) that targets a person or a group of people based on common characteristics such as race, gender, religion and belief, etc. <br><br>
            The corpus contains ~13K tweets in total: 35% are offensive and 11% are hate speech. Vulgar and violence tweets represent 1.5% and 0.7% of the whole corpus. <br><br>
            Ratios of offensive language and hate speech in the corpus are the highest among other corpora without using pre-specified keywords or selecting a specific domain. <br><br>
            More details will be published soon. <br><br>
            <u>We will have 3 shared subtasks:</u> <br><br>
            Subtask 1: Detect whether a tweet is offensive or not.<br>
            Subtask 2: Detect whether a tweet has hate speech or not.<br>
Subtask 3: Detect fine-grained type of hate speech.<br><br>
The same evaluation platform (Codalab) used in OSACT 2020 shared task will be used in the shared tasks. <br><br>
Data will be split into: 70% for training, 10% development, and 20% for testing.<br><br>
We encourage participants to use this data and/or any other external data (previous datasets, lexicons, in-house data, etc.), and try to explain model behavior and study model generalization.
</font></p>
          </div>
        </div>
      </div>
