<div align="center">

<img src="https://freesvg.org/img/1653682897science-svgrepo-com.png" alt="logo" width="200" height="auto" />

<br />

<h1>Datatype Dictionary</h1>

<p>
Dictionary of standard names for biomedical datatypes
</p>

  <h4>
    <a href="datatype_dictionary.json">datatype_dictionary.json</a>
  </h4>
  
<br />

<p>
  <a href="https://github.com/AI-READI/datatype-dictionary/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/AI-READI/datatype-dictionary.svg?style=flat-square" alt="contributors" />
  </a>
  <a href="https://github.com/AI-READI/datatype-dictionary/stargazers">
    <img src="https://img.shields.io/github/stars/AI-READI/datatype-dictionary.svg?style=flat-square" alt="stars" />
  </a>
  <a href="https://github.com/AI-READI/datatype-dictionary/issues/">
    <img src="https://img.shields.io/github/issues/AI-READI/datatype-dictionary.svg?style=flat-square" alt="open issues" />
  </a>
  <a href="https://github.com/AI-READI/datatype-dictionary/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/AI-READI/datatype-dictionary.svg?style=flat-square" alt="license" />
  </a>
</p>
   
<h4>
    <a href="https://github.com/AI-READI/datatype-dictionary/issues/">Report Issues/Make suggestions</a>
  </h4>
</div>

<br />

---

## About
During clinical research studies, multiple modalities of data are typically collected from study participants such as survey answers, blood test results, optical coherence tomography images, electrocardiogram data, magnetic resonance imaging (MRI), etc. Following the [definition provided in the CDS](https://cds-specification.vercel.app/specification/general-principles.html), multiple such modalities can be regrouped as a single datatype if 1) There exists an established standard structure for organizing data from these modalities together, or 2) The modalities were collected through a shared method (instrument, device, etc.), or 3) The modalities cannot be interpreted separately. If none of those apply, a single modality is itself a datatype. 

There are an infinite ways to name a datatype. For instance, data issued from optical coherence tomography imaging can be labeled as "OCT", "oct", "optical coherence tomography", "Optical Coherence Tomography", "oct_imaging", or "OCT data", etc. Having a consistent name for each datatype can faciliate data reuse and interoperability. To our knowledge, there are no standard naming conventions, ontology, or thesaurusThe for biomedical datatypes. The datatype dictionary maintained here is thus intended to achieve that. Established as part of the [AI-READI project](), it has been initiated with datatypes relevant to the AI-READI dataset but the dictionary is meant to expand as more datatypes are included by the biomedical community.

## Structure
The [datatype_dictionary.json](datatype_dictionary.json) file is used to maintain the dicitonary. For each datatype, it contains its standard name, a description of what the datatype represent, links to related terms in popular ontologies/thesaurus if available, etc. It complies with the JSON schema documented under [datatype_dictionary.schema.json](datatype_dictionary.schema.json).

## Contributing

<a href="https://github.com/AI-READI/datatype-dictionary/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AI-READI/datatype-dictionary" />
</a>

Have feedback, suggestions, or questions related to this datatype dictionary? Submit them by opening a [GitHub issue](https://github.com/AI-READI/datatype-dictionary/issues). If you want to suggest changes, you can also submit a PR with suggested changes to the dictionary file or its JSON schema. 

## License

This work is licensed under [MIT](https://opensource.org/licenses/mit). See [LICENSE](LICENSE) for more information.

## How to cite

If you are using the datatype dictionary or any of the associated effort, please cite:

```bash
    Coming soon
```

## Acknowledgements

This project is funded by the NIH under award number 1OT2OD032644. The content is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.

<br />

---

<br />

<div align="center">

<a href="https://aireadi.org">
  <img src="https://github.com/AI-READI/AI-READI-logo/raw/main/logo/png/option2.png" height="200" />
</a>

</div>
