---
title: "“Cristiani no tuvo conocimiento de la masacre que se iba a perpetrar”, dice
  Tojeira."
date: 2017-04-30
hero: "/images/martires-uca-jardin-rosas_2287281260_15086229_667x375.jpg"
excerpt: El sacerdote jesuita y ahora director del Instituto de Derechos Humanos de
  la Universidad (IDHUCA) reveló en el 2017 que retiraría toda acusación contra Alfredo
  Cristiani.
timeToRead: 3
authors: []

---
La UCA solicitó el sobreseimiento del exmandatario salvadoreño por considerar que él no tuvo conocimiento de la masacre que iban a perpetrar un grupo de militares el 16 de noviembre del 1989.

Durante la entrevista del programa República SV de Canal 33, realizada en 2017, José María Tojeira aseguró que pedirían reabrir el caso jesuita, en el cual se involucran a miembros del Alto Mando y del Estado Mayor Conjunto, junto a elementos de la Fuerza Armada, como autores intelectuales y materiales de la masacre de los sacerdotes.

Según Tojeria, a Alfredo Cristiani “no se le informó que iban a matar a los jesuitas, por lo que pedirían (el Idhuca) el sobreseimiento para él”, por lo que quedaría fuera en la reapertura del caso.

Esta noticia, nunca ha sido del agrado para un grupo de personas interesadas en declararlo culpable y desde entonces han tratado de politizarlo, aún cuando el informe de la Comisión de la Verdad, también lo exime de este horrendo crimen.

Dicha investigación identificó a los perpetradores que fueron arrestados para ser juzgados y declarados culpables en 1992, entre ellos un coronel y otros dos oficiales, recalca la Comisión de la Verdad en la página. 44. [http://www.derechoshumanos.net/lesahumanidad/informes/elsalvador/Casos-y-Patrones-de-la-violencia-A-B.pdf](http://www.derechoshumanos.net/lesahumanidad/informes/elsalvador/Casos-y-Patrones-de-la-violencia-A-B.pdf "http://www.derechoshumanos.net/lesahumanidad/informes/elsalvador/Casos-y-Patrones-de-la-violencia-A-B.pdf")

El padre Tojeira, reitera que, con la reapertura del caso jesuitas, se busca llegar a la verdad judicial, opinión que comparte el padre Andreu Oliva, rector de la universidad, por considerar que “el primer proceso fue una farsa”.

Recientemente, el gobierno de Nayib Bukele, quien se caracteriza por atacar deliberadamente a la UCA, anunció que reabriría el caso. Sobre esto, las autoridades de la casa de estudio reaccionaron y pidieron que no deben haber injerencias políticas y ante todo se debe respetar el debido proceso y todas las garantías para que sea un proceso limpio y transparente.

En la cadena nacional del 22 de enero de este año, Nayib Bukele sentenció públicamente a Alfredo Cristiani, acusándolo de haber ordenado la masacre y que no toleraría impunidad.

Para los analistas políticos y organizaciones de la sociedad civil, estas declaraciones del mandatario obedecen a la falta de popularidad y busca llamar la atención hacia este caso, pero deja en impunidad la masacre de El Mozote, donde también hay militares involucrados.

```js
import React from "react";
import { graphql, useStaticQuery } from "gatsby";
import styled from "@emotion/styled";

import * as SocialIcons from "../../icons/social";
import mediaqueries from "@styles/media";

const icons = {
  dribbble: SocialIcons.DribbbleIcon,
  linkedin: SocialIcons.LinkedinIcon,
  twitter: SocialIcons.TwitterIcon,
  facebook: SocialIcons.FacebookIcon,
  instagram: SocialIcons.InstagramIcon,
  github: SocialIcons.GithubIcon,
};

const socialQuery = graphql`
  {
    allSite {
      edges {
        node {
          siteMetadata {
            social {
              name
              url
            }
          }
        }
      }
    }
  }
`;

function SocialLinks({ fill = "#73737D" }: { fill: string }) {
  const result = useStaticQuery(socialQuery);
  const socialOptions = result.allSite.edges[0].node.siteMetadata.social;

  return (
    <>
      {socialOptions.map(option => {
        const Icon = icons[option.name];

        return (
          <SocialIconContainer
            key={option.name}
            target="_blank"
            rel="noopener"
            data-a11y="false"
            aria-label={`Link to ${option.name}`}
            href={option.url}
          >
            <Icon fill={fill} />
          </SocialIconContainer>
        );
      })}
    </>
  );
}
```

But it takes more than good ideas to build and grow a business. It takes people to bring them into reality. Are those people collaborating and sharing their expertise, or are they in conflict and keeping it to themselves?

# This is a primary heading

Do they have the resources necessary to execute on their ideas? Or are they constantly under pressure to pluck only the lowest-hanging fruit through bare minimum means, while putting their greatest ambitions on the back-burner?

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

But it takes more than good ideas to build and grow a business. It takes people to bring them into reality. Are those people collaborating and sharing their expertise, or are they in conflict and keeping it to themselves?

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself. These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself.

## This is a secondary heading

```jsx
import React from "react";
import { ThemeProvider } from "theme-ui";
import theme from "./theme";

export default props => (
  <ThemeProvider theme={theme}>{props.children}</ThemeProvider>
);
```

These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself. These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself. These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself. These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself.

***

Hyphens

***

Asterisks

***

Underscores

These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself. These are the circumstances that suffocate creativity and destroy value in an organization. That’s why I knew that if I was going to start a company, our first product would have to be the company itself.

Do they have the resources necessary to execute on their ideas? Or are they constantly under pressure to pluck only the lowest-hanging fruit through bare minimum means, while putting their greatest ambitions on the back-burner?

Emphasis, aka italics, with _asterisks_ or _underscores_.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

1. First ordered list item
2. Another item
   ⋅⋅* Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
   ⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks


* Or minuses


* Or pluses