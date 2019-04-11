# Memote Meta Study Model Collections

In order to perform the memote meta study, we resorted to various collections of
genome-scale metabolic reconstructions and models. You can find the models in
[`agora/models`](agora/models).

## AGORA

We downloaded version 1.03 of the [AGORA human gut
microbes](https://github.com/VirtualMetabolicHuman/AGORA) (commit
`0c22ff15acaf435c11973fe847bd13b4ea6cc423`). We only used the available SBML
models excluding the ones with additional mucin degradation pathways.

### License

Models in the AGORA collection are distributed under the [CC BY-NC 2.0
license](https://creativecommons.org/licenses/by-nc/2.0/).

## BiGG

We downloaded all available models from the [BiGG Models
database](http://bigg.ucsd.edu/) at the below version. You can find the models
in [`bigg/models`](bigg/models).

```bash
curl 'http://bigg.ucsd.edu/api/v2/database_version'
```

```json
{
  "api_version": "v2",
  "bigg_models_version": "1.3.0",
  "last_updated": "2018-02-24 08:16:33.924054"
}
```

### License

Models in the BiGG database are distributed under a special non-commercial
license.  Please refer to the [full license text](bigg/LICENSE).

## CarveME

We downloaded the [EMBL GEMs
collection](https://github.com/cdanielmachado/embl_gems) (commit
`260d0f133802adbc151de4d7b14fb34722e1d9f4`) created with the
[CarveME](https://github.com/cdanielmachado/carveme) tool. You can find the
models in [`carveme/models`](carveme/models).

### License

Models in the EMBL GEMs collection are distributed under the [CC BY 4.0
license](https://creativecommons.org/licenses/by/4.0/).

## Ebrahim _et al._

We used the SBML level 3 version of the models published in the [M
Model](https://github.com/opencobra/m_model_collection) collection (commit
`afc891b1fd6eb6662c1bfab0369649d8cb9e7e5e`). You can find the
models in [`ebrahim/models`](ebrahim/models).

### License

Please refer to the [model table](ebrahim/model_key.md) in order to see the
individual locations where the models have been published and their licensing
terms.

## OptFlux

We downloaded the SBML models from the [OptFlux models
collection](http://optflux.org/models). You can find the
models in [`optflux/models`](optflux/models).

### License

The collection itself can be considered public domain
[CC0](https://creativecommons.org/publicdomain/zero/1.0/). However, individual
models should be checked for licensing at their origin of publication.

## Path2Models

The [Path2Models collection](https://biomodels-net.github.io/path2models/) is
available via FTP from the [BioModels
database](ftp://ftp.ebi.ac.uk/pub/databases/biomodels/releases/2014-04-11/). We
restricted ourselves to the [whole genome metabolic
models](https://www.ebi.ac.uk/biomodels-main/path2models?cat=genome-scale). You
can find the models in [`path/models`](path/models).

### License

All models in BioModels are public domain under the [CC0
license](https://creativecommons.org/publicdomain/zero/1.0/).

## KBase

We have received a large collection of models via private communication that was
created using the [KBase: The U.S. Department of Energy Systems Biology
Knowledgebase](https://kbase.us/). They are published here for the first time.
You can find the models in [`kbase/models`](kbase/models).

### License

All models in the KBase collection are public domain under the [CC0
license](https://creativecommons.org/publicdomain/zero/1.0/).
