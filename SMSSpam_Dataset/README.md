# SMS Spam Collection v.1

## 1. Description

The **SMS Spam Collection v.1** (referred to as *the corpus*) is a collection of SMS messages in English tagged as either *ham* (legitimate) or *spam*. The dataset consists of **5,574 messages**, making it a valuable resource for SMS spam research.

---

## 1.1 Compilation

The messages were collected from various freely available sources:

- **Grumbletext**: 425 manually extracted spam messages from a UK forum for SMS spam complaints.  
  Source: [Grumbletext](http://www.grumbletext.co.uk/)

- **Caroline Tagg's PhD Thesis**: 450 legitimate (ham) messages.  
  Source: [Thesis PDF](http://etheses.bham.ac.uk/253/1/Tagg09PhD.pdf)

- **NUS SMS Corpus (NSC)**: 3,375 ham messages from the National University of Singapore, mainly contributed by students.  
  Source: [NUS SMS Corpus](http://www.comp.nus.edu.sg/~rpnlpir/downloads/corpora/smsCorpus/)

- **SMS Spam Corpus v.0.1 Big**: 1,002 ham and 322 spam messages from the corpus by José María Gómez Hidalgo.  
  Source: [Corpus Page](http://www.esp.uem.es/jmgomez/smsspamcorpus/)

---

## 1.2 Statistics

| Label | Count | Percentage |
|-------|-------|------------|
| Ham   | 4,827 | 86.6%      |
| Spam  | 747   | 13.4%      |
| **Total** | **5,574** | **100%** |

---

## 1.3 Format

Each line in the dataset represents one SMS message, with two fields separated by a tab character:

```
<label>   <raw text>
```

### Examples:

```
ham   What you doing? how are you?
ham   Ok lar... Joking wif u oni...
spam  FreeMsg: Txt: CALL to No: 86888 & claim your reward...
```

**Note:** Messages are not chronologically sorted.

---

## 2. Usage

The dataset is discussed in the following paper, which includes statistics and baseline machine learning experiments:

**Reference:**
> Almeida, T.A., Gómez Hidalgo, J.M., Yamakami, A.  
> *Contributions to the Study of SMS Spam Filtering: New Collection and Results*.  
> Proceedings of the 2011 ACM Symposium on Document Engineering (ACM DOCENG'11), Mountain View, CA, USA, 2011. (Under review)

---

## 3. About

The corpus was compiled by:

- Tiago Agostinho de Almeida – [Homepage](http://www.dt.fee.unicamp.br/~tiago)  
- José María Gómez Hidalgo – [Homepage](http://www.esp.uem.es/jmgomez)

Special thanks to **Dr. Min-Yen Kan** and his team for the NUS SMS Corpus:  
> [http://www.comp.nus.edu.sg/~kanmy/](http://www.comp.nus.edu.sg/~kanmy/)  
> [SMS Corpus](http://wing.comp.nus.edu.sg:8080/SMSCorpus/)

---

## 4. License / Disclaimer

### Usage Terms:

- Please cite the reference paper and the official dataset page:  
  [http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)

- If you use the corpus, kindly email:  
  `tiago@dt.fee.unicamp.br`

### Legal Notice:

1. Copyright ©  
   Tiago Agostinho de Almeida and José María Gómez Hidalgo

2. **No Warranty / Use at Your Own Risk**  
   The dataset is provided "AS IS" without any warranties.

3. **Limitation of Liability**  
   Authors are not liable for any damages arising from the use of this dataset.

---
