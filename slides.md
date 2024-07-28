---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://eleks.com/wp-content/uploads/Data_mesh_3840x1300-1.jpg
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  A short summary about Data Mesh
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# Data Mesh

What is it about?

[Author: Peter Krauß-Hohl](https://pkrauss-hohl.site)

---

# What is Data Mesh?

<br>

##

Data Mesh is a paradigm that provides a set of principles to change the architectural and organizational approaches to analytical data. Analytical data is a crucial asset to diagnose running businesses and augment them with ML models. To shift from a gut-driven business to a culture of data curiosity and valid experimentation.

<v-click>

## --> and allows to scale them!

</v-click>
<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: https://tse2.mm.bing.net/th?id=OIP.V5CtqS_Ap8ygkqnNwZhmVgAAAA&pid=Api
---

# Core Ideas of Data Mesh

- Decentralized teams and data ownership
- Data Products powered by Domain Driven Design
- Self-serve Shared Data Infrastructure
- Global federated Governance

[Zhamak Dehghani](https://martinfowler.com/articles/data-mesh-principles.html)

[Book - Data Mesh](https://martinfowler.com/articles/data-mesh-principles.html)

---
layout: full
---
# Central Data Team
<img src='/images/central.png' width="600" class="center">

---
layout: image-right
image: './images/microservices-2.png'
---

# Microservices

- Microservices are splitting one application into independent pieces
- Every service is "easy" to deploy/test
- Makes **scaling** (working in parallel) possible
- The services needs to have defined contracts (mostly REST) to work with each other
- Increases the complexity of the application drastically

-> **Exactly the same for data mesh**

---
layout: full
---

# It is difficult
“Organizations which design systems […] are constrained to produce designs which are copies of the communication structures of these organizations.” 

<div grid="~ cols-2 gap 4">
  <img border="rounded" src="/images/org_charts.jpg">
    <div >
      <Tweet id="1551885655877246977" scale="0.65"/>
    </div>
</div>

---
layout: full
---

# Principle of Domain Ownership

* [It follows the Domain Driven Design principles](https://www.domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) (ontology is a quite similar approach)
* Data mesh is founded in **decentralization** and **data responsibility** to ppl who are closest to the data
* They are x-functional (biz, engineers and all data) and the consumer of there own data products

<img src="https://martinfowler.com/articles/data-monolith-to-mesh/data-mesh.png" width="600" class="center">

---
layout: full
---

# Data Products powered by Domain Driven Design

<v-click>

- **Discoverable**
  - Set of meta information to allow the automatic registration in a central registry.

</v-click>
<v-click>

- **Understandable**
  - The specific meaning of coherent data - what kind of entities and the relationships between them

</v-click>

<v-click>

- **Addressable**
  * A data product offers a permanent and unique address to allow the user or system to access it.

</v-click>

<v-click>

- **Natively Accessible**
  - It can be accessed by different personas - scientist (SQL), engineers (API) , analyst(Spreadsheet or SQL)

</v-click>

<v-click>

- **Secure**
  - Encryption, Access Control, Data retention, Regulations, Confidentially Levels

</v-click>

<v-click>

- **Trustworthy**
  - Interval of Change, Timeliness Completeness, Stat shape of data, precision&accuracy over time

</v-click>

<v-click>

- **Interoperable**
  - Type (explicitly defined types), polysemes identifiers, global adress, linking and reuse schema, data linking,

</v-click>

<v-click>

- **Valuable on its own**
  - No need to add more to be generate value

</v-click>

---
layout: image-right
image: https://www.internetworld.de/img/9/9/6/6/2/6/Palantir_w601_h500.jpg
---

# Self-serve Shared Data Infrastructure

* Serve autonomous domain oriented teams
* manage autonomous data products
* integrated platform of operational and analytical capabilities
* designed for generalists
* favor decentralized technologies
* domain agnostic

---
layout: full
---

# Global federated Governance


* Federated Teams
  * Data mesh is a collective responsibility (Domain representatives & Data platform representatives)
* Guiding values
  *  decisions close to the source and identify cross cutting concerns
* Policies
  * distilled set of rules based on the values
* Incentives
  * local and global to resolve prio conflicts
* Platform automations
  * Lineage, discovery, data interfaces, Polysemes identification, data privacy, consent, sovereignty and more


---
layout: image-right
image: https://axenehp.com/wp-content/uploads/2020/02/20200204_header.jpg
---

## What is your perspective about it?

