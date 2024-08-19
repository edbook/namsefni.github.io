Eiginleg heildi
---------------

.. container:: skilgr

   Ef :math:`[a,b]` er lokað bil í :math:`\mathbb{R}` og
   :math:`x_{0},x_{1},\ldots,x_{n}` eru rauntölur þannig að

   .. math:: a = x_{0} < x_{1} < \cdots < x_{n-1} < x_{n} = b

   þá kallast mengið :math:`S = \{x_{0},x_{1},\ldots,x_{n-1},x_{n}\}`
   **skipting** (eða bútun) á bilinu :math:`[a,b]`.

   Bilin :math:`[x_{i-1},x_{i}]` fyrir :math:`i \in \{1,\ldots,n\}`
   nefnast **bútar** skiptingarinnar og talan
   :math:`\Delta x_{i} = x_{i}-x_{i-1}` nefnist **lengd** i-ta bútarins.

   Stærðin :math:`||S|| = \max\{\Delta x_{1},\ldots,\Delta x_{n}\}`
   nefnist svo **norm** skiptingarinnar.

.. container:: ath

   Til upprifjunar þá er stærðin
   :math:`\max\{\Delta x_{1},\ldots,\Delta x_{n}\}` stærsta talan sem
   kemur fyrir í menginu.

.. container:: syn

   skiptingu bils

   Gefið er mengið :math:`[0,1]` og skiptingin
   :math:`S = \left\{0,\frac{1}{3},\frac{1}{2},\frac{5}{6},1\right\}`.
   Tilgreinið alla búta skiptingarinnar, finnið lengd þeirra og
   tilreinum að lokum hvert norm skiptingarinnar er.

   **Lausn:** Bútar skiptingarinnar eru
   :math:`\left[0,\frac{1}{3}\right]`,
   :math:`\left[\frac{1}{3},\frac{1}{2}\right]`,
   :math:`\left[\frac{1}{2},\frac{5}{6}\right]` og
   :math:`\left[\frac{5}{6},1\right]` en lengdir þeirra eru

   .. math::

      \begin{aligned}
      \Delta x_{1} &= x_{1}-x_{0} = \frac{1}{3} - 0 = \frac{1}{3}, \;\;\; \Delta x_{2} = x_{2}-x_{1} = \frac{1}{2} - \frac{1}{3} = \frac{1}{6}\\ \Delta x_{3} &= x_{3}-x_{2} = \frac{5}{6} - \frac{1}{2} = \frac{1}{3} \; \text{ og } \; \Delta x_{4} = x_{4}-x_{3} = 1 - \frac{5}{6} = \frac{1}{6}
      \end{aligned}

   Við sjáum því að norm skiptingarinnar er :math:`||S|| = \frac{1}{3}`.

   .. figure:: Pictures/k2m1.png
      :width: 95.0%

      *Myndræn framsetning á skiptingunni :math:`S` á bilinu
      :math:`[0,1]`.*

.. container:: skilgr

   Ef :math:`S` er skipting á bilinu :math:`[a,b]` og lengd allra búta
   :math:`S` er :math:`\dfrac{b-a}{n}` þar sem :math:`n \in \mathbb{N}`
   þá segjum við að :math:`S` sé **jöfn skipting** á bilinu
   :math:`[a,b]`.

.. container:: ath

   Ljóst er að jafna skiptingin í skilgreiningunni hér á undan hefur
   :math:`n` búta og að hún er ótvírætt ákvörðuð fyrir sérhvert bil
   :math:`[a,b]`. Við munum hér eftir nota tákmálið :math:`I_n` til þess
   að tákna þessa skiptingu.

.. container:: syn

   jafna skiptingu

   Skrifum upp jöfnu skiptinguna með :math:`3` búta fyrir bilið
   :math:`[0,1]` og jöfnu skiptinguna með :math:`5` búta fyrir bilið
   :math:`[0,2]`. Tilgreinum norm skiptinganna í hvoru tilfelli fyrir
   sig.

   **Lausn:** Ef við skiptum :math:`[0,1]` í :math:`3` búta með jafnri
   skiptingu þá er bútlengd hvers bútar
   :math:`\frac{1-0}{3} = \frac{1}{3}`. Skiptingin er því
   :math:`I_{3} = \left\{0,\frac{1}{3},\frac{2}{3},1\right\}`. Ef við
   skiptum svo bilinu :math:`[0,2]` upp í :math:`5` búta með jafnri
   skiptingu þá er bútlengd hvers bútar
   :math:`\frac{2-0}{5} = \frac{2}{5}`. Skiptingin er þar með
   :math:`I_{5} = \left\{0,\frac{2}{5},\frac{4}{5},\frac{6}{5},\frac{8}{5},2\right\}`.

.. container:: skilgr

   Ef :math:`S` og :math:`T` eru tvær skiptingar á bilinu :math:`[a,b]`
   og :math:`S \subseteq T` þá er :math:`S` sögð **grófari** en
   :math:`T`. :math:`T` er einnig sögð vera **fínni** en :math:`S`.

.. container:: ath

   Skilgreiningin hér að ofan segir einfaldlega að ef við byjum með
   einhverja skiptingu :math:`S` á bilinu :math:`[a,b]` og bætum svo
   fleiri skiptipunktum við hana þá fæst skipting sem er fínni en sú sem
   byrjað var með.

.. container:: skilgr

   Gefið er fall :math:`f` á :math:`[a,b]` og skipting
   :math:`S = \{x_{0},\ldots,x_{n}\}`.

   -  Ef til eru tölur :math:`k_{1},\ldots,k_{n}` þannig að

      .. math:: k_{i} \leq f(x) \; \text{ fyrir öll } \; x \in [x_{i-1},x_{i}]

      þá kallast summan

      .. math:: U_{S} = \sum_{i = 1}^{n} k_{i}\Delta x_{i}

      **undirsumma** fyrir fallið :math:`f` á bilinu :math:`[a,b]` með
      tilliti til skiptingarinnar :math:`S`.

.. container:: bluebox

   -  Ef til eru tölur :math:`K_{1},\ldots,K_{n}` þannig að

      .. math:: f(x) \leq K_{i} \; \text{ fyrir öll } \; x \in [x_{i-1},x_{i}]

      þá kallast summan

      .. math:: Y_{S} = \sum_{i = 1}^{n} K_{i}\Delta x_{i}

      **yfirsumma** fyrir fallið :math:`f` á bilinu :math:`[a,b]` með
      tilliti til skiptingarinnar :math:`S`.

   -  Ef við veljum tölur :math:`t_{i} \in [x_{i-1},x_{i}]` fyrir öll
      :math:`i \in \{1,\ldots,n\}` þá kallast summan

      .. math:: \sigma_{S} = \sum_{i = 1}^{n} f\left(t_{i}\right)\Delta x_{i}

      **millisumma** (eða Riemann summa) fyrir fallið :math:`f` á bilinu
      :math:`[a,b]` með tilliti til skiptingarinnar :math:`S`.

.. container:: ath

   Út frá skilgreiningunni er ljóst að fyrir sérhverja skiptingu
   :math:`S` á bili :math:`[a,b]` og fall :math:`f` skilgreint á því
   bili gildir að

   .. math:: U_{S} \leq \sigma_{S} \leq Y_{S}

.. container:: ath

   Í skilgreiningunni hér að ofan var nóg að velja :math:`k_i` sem
   einhverja tölu þannig að :math:`k_i \leq f(x)` fyrir öll
   :math:`x \in [x_{i-1},x_{i}]`. Nema annað sé tekið fram þá munum við
   alltaf ganga út frá að :math:`k_i` hafi verið valið sem **lággildi**
   :math:`f` á bilinu :math:`[x_{i-1},x_{i}]`. Vert er að nefna að til
   eru föll sem hafa ekki endilega lággildi á lokuðu bili, en við munum
   ekki skoða slík föll í þessu hefti. Eins munum við ætíð ganga út frá
   að :math:`K_i` hafi verið valið sem **hágildi** fallisin :math:`f` á
   bilinu :math:`[x_{i-1},x_{i}]`. Að endingu munum við svo alltaf velja
   :math:`t_{i}` sem miðpunkt bilsins :math:`[x_{i-1},x_{i}]`, þ.e.

   .. math:: t_{i} = \frac{x_{i-1}+x_{i}}{2}

.. container:: ath

   Óformlega er hægt er að líta á sérhvern lið í summunum sem flatarmál
   ákveðins ferhyrnings. Ferhyrningarnir sem um ræðir í tilfelli
   undirsummunar eru þeir ferhyrningar sem hafa búta skiptingarinnar sem
   grunnlínu, en hæð þeirra er síðan lægsta gildi fallsins :math:`f` á
   hverjum bút. Fyrir yfir- og millisummuna er um sömu grunnlínur að
   ræða, en hæðirnar eru hæstu gildi :math:`f` í tilfelli yfirsummunar,
   en fallgildi :math:`f` í miðpunktum bútanna í tilfelli millisummunar.

   .. figure:: Pictures/k2m6.png
      :width: 95.0%

      *Myndræn framsetning á undir- og yfirsummu falls :math:`f` með
      skiptinguna :math:`S = \{x_{0},x_{1},x_{2},x_{3}\}` á bilinu
      :math:`[a,b]`.*

   .. figure:: Pictures/k2m7.png
      :width: 95.0%

      *Myndræn framsetning á millisummu falls :math:`f` með skiptinguna
      :math:`S = \{x_{0},x_{1},x_{2},x_{3}\}` á bilinu :math:`[a,b]`.*

.. container:: ath

   Ef :math:`S` er skipting á bili :math:`[a,b]` og við viljum finna há-
   og lágildi falls :math:`f` á öllum bútum skiptingarinnar þá þurfum
   við að gera formerkjamynd fyrir afleiðu :math:`f` og finna útgildi
   fallsins á öllum bútum skiptingarinnar. Það er þó ekki nauðsynlegt í
   öllum tilfellum, t.d. þegar fallið :math:`f` er **einhalla**. Þannig
   fæst að ef :math:`f` er **vaxandi** á bilinu þá mun það taka lágildi
   í vinstri endapunkti sérhvers bútar, en hágildi í hægri
   endapunktinum. Ef :math:`f` er svo **minnkandi** á bilinu þá mun það
   taka hágildi í vinstri endapunkti sérhvers bútar, en lágildi í hægri
   endapunktinum.

.. container:: syn

   undir- yfir- og millisummur Gefið er fallið :math:`f(x) = x^{2}` á
   bilinu :math:`[0,2]` og jafna skiptingin
   :math:`I_4 = \left\{0,\frac{1}{2},1,\frac{3}{2},2\right\}`. Reiknið
   undir-, yfir- og millisummur fallsins :math:`f` m.t.t.
   skiptingarinnar.

   **Lausn** Þar sem fallið :math:`f` er vaxandi á :math:`[0,2]` þá
   tekur það lægstu gildi sýn í vinstri endapunkti sérhvers bútar, en
   hæstu gildi sýn í hægri endapunkti sérhvers bútar. Athugum einnig að
   bútlengd sérhvers bútar er :math:`\frac{1}{2}`. Við fáum því að

   .. math::

      \begin{aligned}
      U_{I_{4}} &= f(0)\cdot\frac{1}{2}+f\left(\frac{1}{2}\right)\cdot\frac{1}{2}+f(1)\cdot\frac{1}{2}+f\left(\frac{3}{2}\right)\cdot\frac{1}{2}\\ &= \frac{1}{2}\cdot\left(0^{2}+\left(\frac{1}{2}\right)^{2}+1^{2}+\left(\frac{3}{2}\right)^{2}\right) = 1.75
      \end{aligned}

   .. figure:: Pictures/k2m2.png
      :width: 80.0%

      *Myndræn framsetning á undursummu :math:`f` m.t.t. skiptingarinnar
      :math:`I_4`.*

   Eins fæst að yfirsumman er

   .. math::

      \begin{aligned}
      Y_{I_{4}} &= f\left(\frac{1}{2}\right)\cdot\frac{1}{2}+f\left(1\right)\cdot\frac{1}{2}+f\left(\frac{3}{2}\right)\cdot\frac{1}{2}+f\left(2\right)\cdot\frac{1}{2}\\ &= \frac{1}{2}\cdot\left(\left(\frac{1}{2}\right)^{2}+1^{2}+\left(\frac{3}{2}\right)^{2}+2^{2}\right) = 3.75
      \end{aligned}

   Við sjáum svo að miðpunktar bútanna eru :math:`t_{1} = \frac{1}{4}`,
   :math:`t_{2} = \frac{3}{4}`, :math:`t_{3} = \frac{5}{4}` og
   :math:`t_{4} = \frac{7}{4}`. Millisumman er því

   .. math::

      \begin{aligned}
      \sigma_{I_{4}} &= f\left(\frac{1}{4}\right)\cdot\frac{1}{2}+f\left(\frac{3}{4}\right)\cdot\frac{1}{2}+f\left(\frac{5}{4}\right)\cdot\frac{1}{2}+f\left(\frac{7}{4}\right)\cdot\frac{1}{2}\\ &= \frac{1}{2}\cdot\left(\left(\frac{1}{4}\right)^{2}+\left(\frac{3}{4}\right)^{2}+\left(\frac{5}{4}\right)^{2}+\left(\frac{7}{4}\right)^{2}\right) = 2.625
      \end{aligned}

   .. figure:: Pictures/k2m3.png
      :width: 80.0%

      *Myndræn framsetning á yfirsummu :math:`f` m.t.t. skiptingarinnar
      :math:`I_4`.*

   .. figure:: Pictures/k2m4.png
      :width: 80.0%

      *Myndræn framsetning á millisummu :math:`f` m.t.t. skiptingarinnar
      :math:`I_4`.*

.. container:: syn

   undir- yfir- og millisummur Gefið er fallið
   :math:`f(x) = \frac{1}{x}` á bilinu :math:`[1,2]` og skiptingin
   :math:`S = \left\{1,\frac{4}{3},\frac{3}{2},2\right\}`. Reiknið
   undir-, yfir- og millisummur fallsins :math:`f` m.t.t.
   skiptingarinnar.

   **Lausn:** Athugum að fallið :math:`f(x) = \frac{1}{x}` er minnkandi
   á bilinu :math:`[1,2]`. Þar með tekur það lággildi í hægri
   endapunktum sérhvers bútar, en hágildi í þeim vinstri. Við fáum þar
   með

   .. math::

      \begin{aligned}
      U_{S} &= f\left(\frac{4}{3}\right)\cdot \Delta x_{1} + f\left(\frac{3}{2}\right)\cdot\Delta x_{2} + f\left(2\right)\cdot \Delta x_{3}\\ &= \frac{3}{4}\cdot\frac{1}{3} + \frac{2}{3}\cdot\frac{1}{6} + \frac{1}{2}\cdot\frac{1}{2} = \frac{11}{18} = 0.611
      \end{aligned}

   og eins

   .. math::

      \begin{aligned}
      Y_{S} &= f\left(1\right)\cdot \Delta x_{1} + f\left(\frac{4}{3}\right)\cdot\Delta x_{2} + f\left(\frac{3}{2}\right)\cdot \Delta x_{3}\\ &= 1\cdot\frac{1}{3}+\frac{3}{4}\cdot\frac{1}{6}+\frac{2}{3}\cdot\frac{1}{2} = \frac{19}{24} = 0.792
      \end{aligned}

   Við sjáum svo að miðpunktar bútanna eru :math:`t_{1} = \frac{7}{6}`,
   :math:`t_{2} = \frac{17}{12}` og :math:`t_{3} = \frac{7}{4}`.
   Millisumman er því

   .. math::

      \begin{aligned}
      \sigma_{S} &= f\left(\frac{7}{6}\right)\cdot\Delta x_{1} + f\left(\frac{17}{12}\right)\cdot\Delta x_{2} + f\left(\frac{7}{4}\right)\cdot\Delta x_{3}\\
      &= \frac{6}{7}\cdot\frac{1}{3}+\frac{12}{17}\cdot\frac{1}{6}+\frac{4}{7}\cdot\frac{1}{2} = \frac{82}{119} = 0.689
      \end{aligned}

.. container:: syn

   undir- og yfirsummur Gefið er fallið :math:`f(x) = x^3-2x^2+1` á
   bilinu :math:`\left[-\frac{1}{2},2\right]`. Gerið formerkjamynd fyrir
   afleiðu :math:`f` og notið hana svo til þess að reikna undir- og
   yfirsummu fallsins á bilinu m.t.t. skiptingarinnar
   :math:`S =\left\{-\frac{1}{2},\frac{1}{2},1,2\right\}`.

   **Lausn:** Byrjum á að diffra :math:`f`, fáum
   :math:`f'(x) = 3x^{2}-4x = x\left(3x-4\right)`. Sjáum því að
   :math:`f'(x) = 0` ef :math:`x = 0` eða :math:`x = \frac{4}{3}`.
   Prófun gefur svo að :math:`f'(x) < 0` ef
   :math:`x \in \left]0,\frac{4}{3}\right[` en :math:`f'(x) > 0` ef
   :math:`x \in \left[-\frac{1}{2},0\right[ \cup \left]\frac{4}{3},2\right]`.


   Við getum nú notast við formerkjamyndina hér að ofan til þess að
   reikna undir- og yfirsummur :math:`f` m.t.t :math:`S`. Byrjum á
   undirsummunni.

   Á bútnum :math:`\left[-\frac{1}{2},\frac{1}{2}\right]` tekur
   :math:`f` lágildi í öðrum hvorum endapunktinum. Við höfum að
   :math:`f\left(-\frac{1}{2}\right) = \frac{3}{8}` en
   :math:`f\left(\frac{1}{2}\right) = \frac{5}{8}` svo :math:`f` hefur
   þar með lágildi í vinstri endapunktinum á þessum bút. Á bútnum
   :math:`\left[\frac{1}{2},1\right]` hefur :math:`f` lágildi í hægri
   endapunktinum og á bútnum :math:`\left[1,2\right]` hefur :math:`f`
   svo lágildi í :math:`x = \frac{4}{3}`. Við fáum þar með:

   .. math::

      \begin{aligned}
      U_{S} &= f\left(-\frac{1}{2}\right)\Delta x_{1}+f\left(1\right)\Delta x_{2}+f\left(\frac{4}{3}\right)\Delta x_{3}\\ &= \frac{3}{8}\cdot1+0\cdot\frac{1}{2}-\frac{5}{27}\cdot 1 = \frac{41}{216} = 0.190
      \end{aligned}

   Skoðum nú yfirsummuna. Á bútnum
   :math:`\left[-\frac{1}{2},\frac{1}{2}\right]` tekur :math:`f` hágildi
   í :math:`x = 0`, á bútnum :math:`\left[\frac{1}{2},1\right]` tekur
   fallið hágildi í vinstri endapunktinum en á bútnum
   :math:`\left[1,2\right]` tekur :math:`f` hágildi í öðrum hvorum
   endapunktinum. Þar sem :math:`f(1) = 0` en :math:`f(2) = 1` þá tekur
   fallið hágildi í hægri endapunkti bútarins. Við fáum þar með:

   .. math::

      \begin{aligned}
      Y_{S} &= f(0)\Delta x_{1} + f\left(\frac{1}{2}\right)\Delta x_{2} + f(2)\Delta x_{3}\\ &= 1\cdot1 + \frac{5}{8}\cdot\frac{1}{2} + 1\cdot1 = \frac{37}{16} = 2.313
      \end{aligned}

   .. figure:: Pictures/k2m9.png
      :width: 95.0%

      *Myndræn framsetning á undir- og yfirsummu fallsins :math:`f`
      m.t.t skiptingarinnar :math:`S`.*

.. container:: hregla

   Gerum ráð fyrir því að :math:`S = \{x_{0},\ldots,x_{n}\}` sé skipting
   á bilinu :math:`[a,b]` og að :math:`m \in [a,b]` sé ekki í menginu
   :math:`S`. Þá er :math:`S_{m} = S \cup \{m\}` einnig skipting á
   bilinu og fyrir sérhvert samfellt fall :math:`f` á :math:`[a,b]`
   gildir að

   .. math:: U_{S_{m}} \geq U_{S} \; \text{ og } \; Y_{S} \geq Y_{S_{m}}

.. container:: sonnun

   Þar sem talan :math:`m` er ekki í menginu :math:`S` en á bilinu
   :math:`[a,b]` þá er þar með til tala :math:`j` þannig að
   :math:`x_{j-1} < s < x_{j}`. Skiptingin :math:`I_{m}` er því eins og
   :math:`I` nema að bútnum :math:`[x_{j-1},x_{j}]` hefur verið skipt út
   en bútunum :math:`[x_{j-1},m]` og :math:`[m,x_{j}]` hefur verið skipt
   inn.

   Táknum nú lægstu gildi :math:`f` á bútunum :math:`[x_{j-1},m]` og
   :math:`[m,x_{j}]` með :math:`l_{1}` og :math:`l_{2}`. Þá er ljóst að
   :math:`k_{j} \leq l_{1}` og :math:`k_{j} \leq l_{2}` þar sem
   :math:`k_{j}` er lægsta gildi :math:`f` á öllum bútnum
   :math:`[x_{j-1},x_{j}]`. Skoðum nú mismuninn
   :math:`U_{S_{m}} - U_{S}`. Við fáum

   .. math::

      \begin{aligned}
      U_{S_{m}} - U_{S} &= \sum_{i= 1, i \neq j}^{n} k_{i}\Delta x_{i} + l_{1}\left(m-x_{j-1}\right)+l_{2}\left(x_{j} - m\right) - \sum_{i = 1}^{n} k_{i}\Delta x_{i}\\ &= l_{1}\left(m-x_{j-1}\right)+l_{2}\left(x_{j} - m\right) - k_{j}\Delta x_{j}\\ &\geq k_{j}\left(m-x_{j-1}\right)+k_{j}\left(x_{j} - m\right) - k_{j}\Delta x_{j}\\ &= k_{j}m-k_{j}x_{j-1}+k_{j}x_{j}-k_{j}m-k_{j}\Delta x_{j}\\ &= k_{j}(x_{j}-x_{j-1})-k_{j}\Delta x_{j} = k_{j}\Delta x_{j} - k_{j}\Delta x_{j} = 0
      \end{aligned}

   Þ.e :math:`U_{S_{m}} - U_{S} \geq 0` og því
   :math:`U_{S_{m}} \geq U_{S}`.

   Sönnunin á ójöfnunni :math:`Y_{S} \geq Y_{S_{m}}` er sambærileg
   sönnuninni hér á undan og er eftirlátin nemendum.

.. container:: regla

   Ef :math:`S` og :math:`T` eru bútanir á bilinu :math:`[a,b]` og
   :math:`T` er fínni en :math:`S` þá gildir fyrir öll samfelld föll á
   bilinu :math:`[a,b]` að

   .. math:: U_{S} \leq U_{T} \; \text{ og } \; Y_{T} \leq Y_{S}

.. container:: ath

   Reglan hér á undan er sönnuð með því að notast ítrekað við
   hjálparregluna, við eftirlátum nemendum að útfæra sönnunina.

.. container:: ath

   Á mannamáli segir reglan okkur að því fínni sem við gerum skiptinguna
   okkar, því hærra verður gildið á undirsummunni en því lægra á
   yfirsummunni. Því nálgast þessi gildi hvort annað þegar skiptingin er
   gerð fínni.

.. container:: regla

   Ef :math:`S` og :math:`T` eru bútanir á bilinu :math:`[a,b]` þá
   gildir fyrir öll samfelld föll :math:`f` á bilinu að

   .. math:: U_{S} \leq Y_{T}

.. container:: sonnun

   Athugum að :math:`V = S \cup T` er skipting á :math:`[a,b]` sem er
   fínni en bæði :math:`S` og :math:`T`. Við fáum því

   .. math:: U_{S} \leq U_{V} \leq Y_{V} \leq Y_{T}

.. container:: ath

   Með öðrum orðum, allar undirsummur hafa lægra gildi en allar
   yfirsummur.

.. container:: skilgr

   Ef :math:`A \subseteq \mathbb{R}` og til er tala :math:`K` þannig að
   :math:`K \geq x` fyrir öll :math:`x \in A` þá er sagt að mengið
   :math:`A` sé **takmarkað að ofan**. Eins er sagt að mengið :math:`A`
   sé **takmarkað að neðan** ef til er tala :math:`k` þannig að
   :math:`k \leq x` fyrir öll :math:`x \in A`.

.. container:: frumsenda

   um fullkomleika :math:`\mathbb{R}` Ef mengi :math:`A` er takmarkað að
   ofan þá er til minnsta tala :math:`K \in \mathbb{R}` sem uppfyllir
   skilyrðið :math:`K \geq x` fyrir öll :math:`x \in A`. Hún er táknuð
   með :math:`\sup(A)` og nefnist **efra mark** mengisins :math:`A`.

   Eins gildir að ef mengið :math:`A` er takmarkað að neðan þá er til
   stærsta tala :math:`k \in \mathbb{R}` sem uppfyllir skilyrðið
   :math:`k \leq x` fyrir öll :math:`x \in A`. Hún er táknuð með
   :math:`\inf(A)` og nefnist **neðra mark** mengisins :math:`A`.

.. container:: ath

   Í þeim tilfellum þar sem mengi :math:`A` hefur minnsta stak
   :math:`\min(A)` þá gildir að :math:`\inf(A) = \min(A)`, og eins
   gildir að ef :math:`A` hefur stærsta stak :math:`\max(A)` þá gildir
   að :math:`\sup(A) = \max(A)`. Mengi :math:`A` þarf þó ekki að hafa
   minnsta og/eða stærsta stak til þess að stærðirnar :math:`\inf(A)` og
   :math:`\sup(A)` séu vel skilgreindar. Ef við setjum t.d.
   :math:`A = ]0,1[` þá gildir að :math:`\inf(A) = 0` og
   :math:`\sup(A) = 1`, en :math:`A` hefur hvorki minnsta né stærsta
   stak.

.. container:: skilgr

   Látum :math:`f` vera fall á bili :math:`[a,b]`. Efra mark mengis
   allra undirsumma :math:`f` á bilinu nefnist þá **neðra heildi**
   fallsins :math:`f` yfir bilið og er táknað með
   :math:`\underline{I}(f)`. Neðra mark mengis allra yfirsumma :math:`f`
   á bilinu nefnist svo **efra heildi** fallsins :math:`f` yfir bilið og
   er táknað með :math:`\overline{I}(f)`.

.. container:: ath

   Regla :math:`2.3` tryggir að neðra- og efra heild falls :math:`f` á
   bili :math:`[a,b]` er vel skilgreint og að
   :math:`\underline{I}(f) \leq \overline{I}(f)`.

.. container:: skilgr

   Eiginlegt heildi Ef um fall :math:`f` á bili :math:`[a,b]` gildir að
   :math:`L = \underline{I}(f) = \overline{I}(f)` þá er fallið sagt
   **heildanlegt** yfir bilið :math:`[a,b]`. Talan :math:`L` kallast
   **eiginlega heildi** fallsins :math:`f` yfir bilið :math:`[a,b]`. Við
   táknum eiginlega heildið með

   .. math:: \int_{a}^{b} f(x)\;dx

   Tölurnar :math:`a` og :math:`b` nefnast **heildismörk** heildisins.

.. container:: ath

   Með öðrum orðum má segja að ef til er **nákvæmlega ein** tala sem er
   stærri en eða jöfn öllum undirsummum og minni en eða jöfn öllum
   yfirsummum þá er fallið :math:`f` heildanlegt yfir bilið
   :math:`[a,b]`, en talan sem um ræðir er ákveðna heildi fallsins yfir
   bilið.

.. container:: ath

   Umfjöllun um eiginleg heildi og flatarmál.

.. container:: skilgr

   Ef :math:`f` er heildanlegt fall á bilinu :math:`[a,b]` þá
   skilgreinum við heildið

   .. math:: \int_{b}^{a} f(x) \; dx = -\int_{a}^{b} f(x) \; dx

.. container:: ath

   Við megum með öðrum orðum víxla á heildismörkunum í eiginlegu heildi
   ef við víxlum einnig formerkinu.

.. container:: regla

   Ef :math:`f` er heildanlegt fall á bilinu :math:`[a,b]` og
   :math:`c \in [a,b]` þá gildir

   .. math:: \int_{a}^{b} f(x) \; dx = \int_{a}^{c} f(x) \; dx + \int_{c}^{b} f(x) \; dx

.. container:: monnun

   .. figure:: Pictures/k2m5.png
      :width: 80.0%

      *Myndræn framsetning á reglunni hér á undan. Samanlagt flatarmál
      bláa og rauða svæðisins er jafnt flatarmáli græna svæðisins.*

.. container:: regla

   Ef :math:`f` og :math:`g` eru heildanleg föll á bili :math:`[a,b]` og
   :math:`c \in \mathbb{R}` þá gildir:

   -  :math:`\displaystyle \int_{a}^{b} f(x) + g(x) \; dx = \int_{a}^{b} f(x) \; dx + \int_{a}^{b} g(x) \; dx`

   -  :math:`\displaystyle \int_{a}^{b} c\cdot f(x) \; dx = c\cdot\int_{a}^{b} f(x) \; dx`

.. container:: regla

   Gerum ráð fyrir því að :math:`S_{n}` sé skipting á bilinu
   :math:`[a,b]` fyrir sérhvert :math:`n \in \mathbb{N}`. Ef :math:`f`
   er fall á bilinu þannig að

   .. math:: \lim_{n \to \infty} U_{S_{n}} = \lim_{n \to \infty} Y_{S_{n}} = L

   þá er fallið :math:`f` heildanlegt yfir bilið :math:`[a,b]` og

   .. math:: \int_{a}^{b} f(x) \; dx = L

.. container:: syn

   eiginleg heildi Reiknum eiginlega heildi fallsins :math:`f(x) = x^2`
   yfir bilið :math:`[0,1]`. Notfærum okkur að
   :math:`\displaystyle \sum_{k = 1}^{n} k^{2} = \frac{n(n+1)(2n+1)}{6}`.

   **Lausn:** Byrjum á að reikna
   :math:`\displaystyle \lim_{n \to \infty} U_{I_{n}}`. Athugum að
   billengd sérhvers bútar í skiptingunni :math:`I_n` er
   :math:`\frac{1-0}{n} = \frac{1}{n}` og að fallið :math:`f` er vaxandi
   svo lægsta gildi þess er tekið í vinstri endapunkti sérhvers bútar.
   Við sjáum einnig að :math:`x_{k} = \frac{k}{n}` og því fæst:

   .. math::

      \begin{aligned}
      U_{I_{n}} &= \sum_{k = 1}^{n} x_{k-1}^{2}\cdot\Delta x_{k}\\ &= \sum_{k = 1}^{n} \left(\frac{k-1}{n}\right)^{2}\cdot\frac{1}{n}\\ &= \frac{1}{n^{3}}\cdot\sum_{k = 0}^{n-1} k^{2} = \frac{1}{n^{3}}\cdot\sum_{k = 1}^{n-1} k^{2}\\ &= \frac{1}{n^{3}} \cdot \frac{(n-1)n(2n-1)}{6}\\ &= \frac{2n^{3}-3n^{2}+n}{6n^{3}} = \frac{1}{3}-\frac{1}{2n}+\frac{1}{6n^{2}}
      \end{aligned}

   Þar með fæst að
   :math:`\displaystyle \lim_{n \to \infty} U_{I_{n}} = \frac{1}{3}`.

   Þegar yfirsumman m.t.t. :math:`I_{n}` er reiknuð þá notfærum við
   okkur að hæsta fallgildi :math:`f` á hverjum bút er tekið í hægri
   endapunkta bútarins og fáum með sambærilegum hætti og hér að ofan að

   .. math:: Y_{I_{n}} = \sum_{k = 1}^{n}x_{k}^{2}\Delta x_{k} = \frac{2n^{3}+3n^{2}+n}{6n^{3}} = \frac{1}{3}+\frac{1}{2n}+\frac{1}{6n^{2}}

   og þar með
   :math:`\displaystyle \lim_{n \to \infty} Y_{I_{n}} = \frac{1}{3}`.

   Við fáum því að

   .. math:: \int_{0}^{1} x^{2}\;dx = \frac{1}{3}

.. container:: regla

   Meðalgildisreglan fyrir heildi Ef :math:`f` er samfellt fall á bili
   :math:`[a,b]` þá er til tala :math:`c \in [a,b]` þannig að

   .. math:: f(c) = \frac{1}{b-a}\int_{a}^{b} f(x) \; dx

.. container:: sonnun

   Setjum :math:`S = \{a,b\}`. Þá er :math:`S` skipting á bilinu
   :math:`[a,b]` og því gildir að

   .. math:: U_{S} \leq \int_{a}^{b} f(x) \; dx \leq Y_{S}

   Ef við látum nú :math:`k` vera lággildi :math:`f` á :math:`[a,b]` en
   :math:`K` hágildi þess á bilinu þá höfum við þar með

   .. math:: k(b-a) \leq \int_{a}^{b} f(x) \; dx \leq K(b-a)

   og því

   .. math:: k \leq \frac{1}{b-a}\int_{a}^{b} f(x) \; dx \leq K

   Milligildisreglan fyrir samfelld föll gefur því að til er
   :math:`c \in [a,b]` þannig að

   .. math:: f(c) = \frac{1}{b-a}\int_{a}^{b} f(x) \; dx

   .. figure:: Pictures/k2m10.png
      :width: 80.0%

      *Myndræn framsetning á meðalgildisreglunni fyrir heildi.
      Flatarmálið undir ferli fallsins :math:`f` á bilinu :math:`[a,b]`
      er jafnt :math:`\displaystyle \int_{a}^{b} f(x)\;dx = f(c)(b-a)`*

.. container:: regla

   Undirstöðusetning stærðfræðigreiningarinnar Ef :math:`f` er samfellt
   fall á :math:`[a,b]` og við skilgreinum fyrir öll :math:`x \in [a,b]`
   fallið

   .. math:: F(x) = \int_{a}^{x} f(t)\;dt

   þá gildir að :math:`F'(x) = f(x)`.

.. container:: sonnun

   Byrjum á að skoða afleiðuna frá hægri, fáum:

   .. math::

      \begin{aligned}
      F'_{+}(x) &= \lim_{h \to 0^{+}} \dfrac{F(x+h)-F(x)}{h}\\ &= \lim_{h \to 0^{+}} \dfrac{\int_{a}^{x+h}f(t)\;dt - \int_{a}^{x}f(t)\;dt}{h}\\ &= \lim_{h \to 0^{+}} \dfrac{\int_{x}^{x+h}f(t)\;dt}{h}\\ &= \lim_{h \to 0^{+}} \frac{1}{h}\int_{x}^{x+h}f(t)\;dt
      \end{aligned}

   Athugum nú að lengd bilsins :math:`[x,x+h]` er :math:`h`, og því
   gefur meðalgildisreglan fyrir heildi að fyrir sérhvert :math:`h>0` er
   til tala :math:`c_{h}` á bilinu :math:`[x,x+h]` þannig að

   .. math:: f\left(c_{h}\right) = \frac{1}{h}\int_{x}^{x+h}f(t)\;dt

   Þegar :math:`h` stefnir á :math:`0` þá hlítur svo talan :math:`c_{h}`
   að vera að stefna á :math:`x` þar sem hún er klemmd á milli :math:`x`
   og :math:`x+h`. Samfelldni fallsins :math:`f` gefur því:

   .. math::

      \begin{aligned}
      F'_{+}(x) = \lim_{h \to 0^{+}} f\left(c_{h}\right) = f(x) 
      \end{aligned}

   Tilfellið fyrir vinstri afleiðuna er sambærilegt, við þurfum einungis
   að athuga að í því tilfelli er talan :math:`c_h` á bilinu
   :math:`[x+h,x]` og við þurfum að huga örlítið að formerkjum í
   útreikningum okkar. Nemendum er eftirlátið að fylla í eyðurnar.

.. container:: ath

   Í reglunni hér að ofan túlkum við :math:`F'(a)` sem afleiðu fallsins
   :math:`F` frá hægri, en :math:`F'(b)` sem afleiðu fallsins :math:`F`
   frá vinstri.

.. container:: regla

   Undirstöðusetning stærðfræðigreiningarinnar - 2. útgáfa Ef :math:`f`
   er samfellt fall á :math:`[a,b]` og :math:`F` er stofnfall fyrir
   :math:`f` þá gildir

   .. math:: \int_{a}^{b}f(x)\;dx = F(b) - F(a)

.. container:: sonnun

   Ef við skilgreinum :math:`G(t) = \int_{a}^{t}f(x)\;dx` þá er
   :math:`G` stofnfall fyrir :math:`f` skv. meginsetningu
   stærðfræðigreiningarinnar. Ef :math:`F` er eitthvert annað stofnfall
   fyrir :math:`G` þá gildir svo að til er fasti :math:`k` þannig að

   .. math:: F(t) = G(t) + k

   Þar sem :math:`G(a) = 0` þá fæst þar með að :math:`F(a) = k` og því
   fáum við

   .. math:: G(t) = F(t) - k = F(t) - F(a)

   Setjum :math:`t = b` og fáum svo

   .. math:: \int_{a}^{b} f(x)\;dx = G(b) = F(b)-F(a)

.. container:: ath

   Mjög algengt er að notast við ritháttinn
   :math:`\displaystyle \Biggl[F(x)\Biggr]_{a}^{b}` fyrir
   :math:`F(b) - F(a)`. Við getum þá skrifað regluna hér á undan sem

   .. math:: \int_{a}^{b}f(x)\;dx = \Biggl[F(x)\Biggr]_{a}^{b} = F(b) - F(a)

.. container:: syn

   ákveðin heildi Reiknum eftirfarandi ákveðnu heildi:

   -  :math:`\displaystyle \int_{1}^{2} 2x^{2}-x+1 \; dx`

   -  :math:`\displaystyle \int_{4}^{5} \frac{2}{x-3} \; dx`

   -  :math:`\displaystyle \int_{0}^{1} 5\cos(\pi x) \; dx`

   **Lausn:**

   -  

      .. math::

         \begin{aligned}
         \int_{1}^{2} 3x^{2}-x+1 \; dx = \Biggl[x^{3}-\frac{1}{2}x^{2}+x\Biggr]_{1}^{2} = 2^{3}-\frac{1}{2} \cdot 2^{2}+2 - \left(1^{3}-\frac{1}{2} \cdot 1 + 1\right) = 6.5
         \end{aligned}

   -  

      .. math::

         \begin{aligned}
         \int_{4}^{5} \frac{2}{x-3} \; dx = 2\cdot\Biggl[\ln(x-3)\Biggr]_{4}^{5} = 2\cdot\left(\ln(5)-\ln(4)\right) = 2\ln\left(\frac{5}{4}\right) = 0.446
         \end{aligned}

   -  

      .. math::

         \begin{aligned}
         \int_{0}^{1} 5\cos(\pi x) \; dx = 5\cdot\Biggl[\frac{1}{\pi}\sin(\pi x)\Biggr]_{0}^{1} = \frac{5}{\pi}\cdot\left(\sin(\pi)-\sin(0)\right) = 0
         \end{aligned}

.. container:: æd

   Reiknið eftirfarandi ákveðnu heildi:

   -  :math:`\displaystyle \int_{1}^{3} -x^{2}+x+3 \; dx`

   -  :math:`\displaystyle \int_{0}^{1} 3^{x} \; dx`

   -  :math:`\displaystyle \int_{\pi}^{2\pi} 2\sin(x) \; dx`

.. container:: regla

   Hlutheildun - Ákveðin heildi Ef :math:`f` er heildanlegt fall á bili
   :math:`[a,b]` og :math:`g` diffranlegt á sama bili þá gildir að

   .. math:: \int_{a}^{b} f(x)g'(x) \; dx = \Biggl[f(x)g(x)\Biggr]_{a}^{b} - \int_{a}^{b} f'(x)g(x)\;dx

.. container:: syn

   hlutheildun Reiknum eftirfarandi heildi með því að notast við
   hlutheildun.

   -  :math:`\displaystyle \int_{0}^{1} xe^{x} \; dx`

   -  :math:`\displaystyle \int_{0}^{\pi} x\sin(x) \; dx`

   -  :math:`\displaystyle \int_{1}^{e} 2x^{2}\ln(x) \; dx`

   **Lausn:**

   -  Við veljum :math:`f(x) = x` og :math:`g'(x) = e^{x}`. Þá er
      :math:`f'(x) = 1` og :math:`g(x) = e^{x}` og við fáum því:

      .. math::

         \begin{aligned}
         \int_{0}^{1} xe^{x}\;dx &= \Biggl[xe^{x}\Biggr]_{0}^{1}-\int_{0}^{1}e^{x}\;dx = 1\cdot e^{1}-0\cdot e^{0} - \Biggl[e^{x}\Biggr]_{0}^{1}\\ &= e - \left(e^{1}-e^{0}\right) = e^{0} = 1
         \end{aligned}

   -  Veljum :math:`f(x) = x` og :math:`g'(x) = \sin(x)`. Þá er
      :math:`f'(x) = 1` og :math:`g(x) = -\cos(x)` svo við fáum:

      .. math::

         \begin{aligned}
         \int_{0}^{\pi} x\sin(x) \; dx &= \Biggl[-x\cos(x)\Biggr]_{0}^{\pi} + \int_{0}^{\pi} \cos(x) \; dx = -\pi\cos(\pi)-(-0\cdot\cos(0)) + \Biggl[\sin(x)\Biggr]_{0}^{\pi}\\ &= \pi + (\sin(\pi)-\sin(0)) = \pi
         \end{aligned}

   -  Veljum :math:`f(x) = \ln(x)` og :math:`g'(x) = 2x^{2}`. Þá er
      :math:`f'(x) = \frac{1}{x}` og :math:`g(x) = \frac{2}{3}x^{3}`.
      Því fæst:

      .. math::

         \begin{aligned}
         \int_{1}^{e} 2x^{2}\ln(x) \; dx &= \Biggl[\frac{2}{3}x^{3}\ln(x)\Biggr]_{1}^{e} - \int_{1}^{e} \frac{2}{3}x^{2} \; dx = \frac{2}{3}e^{3}\ln(e)-\frac{2}{3}e^{1}\ln(1) - \Biggl[\frac{2}{9}x^{3}\Biggr]_{1}^{e}\\ &= \frac{2}{3}e^{3}-\left(\frac{2}{9}e^{3}-\frac{2}{9}\cdot 1^{3}\right) = \frac{2}{9}\left(2e^{3}+1\right)
         \end{aligned}

.. container:: æd

   Reiknið eftirfarandi heildi með því að notast við hlutheildun.

   -  :math:`\displaystyle \int_{0}^{2} x2^{x} \; dx`

   -  :math:`\displaystyle \int_{0}^{\pi} x\cos(2x) \; dx`

   -  :math:`\displaystyle \int_{1}^{2} \sqrt{x}\ln(x) \; dx`

.. container:: regla

   Innsetningarregla - Ákveðin heildi Tökum föll :math:`f` og :math:`g`
   og bil :math:`[a,b]` þannig að :math:`f\circ g` sé heildanlegt á
   :math:`g\left([a,b]\right)` og :math:`g` diffranlegt. Ef
   :math:`u = g(x)` þá er :math:`du = g'(x)\;dx` og

   .. math:: \int_{a}^{b} f(g(x))\cdot g'(x)\;dx = \int_{g(a)}^{g(b)} f(u)\;du

.. container:: syn

   innsetningu Reiknum eftirfarandi heildi með því að notast við
   innsetningu.

   -  :math:`\displaystyle \int_{-1}^{1} 3x^{2}\left(x^{3}+1\right)^{5} \; dx`

   -  :math:`\displaystyle \int_{e}^{e^{2}} \frac{\ln(\ln(x))}{x}  \; dx`

   -  :math:`\displaystyle \int_{0}^{\frac{\pi}{2}} \cos(x)\sin^{2}(x) \; dx`

   **Lausn:**

   -  Setjum :math:`u = x^{3}+1`. þá er :math:`du = 3x^{2} \; dx`.
      Athugum einnig að ef :math:`x = -1` þá höfum við :math:`u = 0` og
      ef :math:`x = 1` þá fæst :math:`u = 2`. Við fáum því

      .. math:: \int_{-1}^{1} 3x^{2}\left(x^{3}+1\right)^{5} \; dx = \int_{0}^{2} u^{5} \; du = \Biggl[\frac{1}{6}u^{6}\Biggr]_{0}^{2} = \frac{32}{3}

   -  Setjum nú :math:`u = \ln(x)`. Þá er :math:`du = \frac{1}{x}\; dx`.
      Einnig höfum við að ef :math:`x = e` þá er :math:`u = 1` og ef
      :math:`x = e^{2}` þá er :math:`u = 2`. Því fæst

      .. math::

         \begin{aligned}
         \int_{e}^{e^{2}} \frac{\ln(\ln(x))}{x}  \; dx &= \int_{1}^{2} \ln(u) \; du = \Biggl[u\ln(u)-u\Biggr]_{1}^{2}\\ &= 2\ln(2)-2-\left(1\cdot\ln(1)-1\right)\\ &= \ln(4)-1 = 0.386
         \end{aligned}

   -  Hér setjum við :math:`u = \sin(x)`. Þá höfum við að
      :math:`du = \cos(x) \; dx`. Einnig höfum við að þegar
      :math:`x = 0` þá er :math:`u = 0` og þegar
      :math:`x = \frac{\pi}{2}` þá er :math:`u = 1`. Við fáum því

      .. math:: \int_{0}^{\frac{\pi}{2}} \cos(x)\sin^{2}(x) \; dx = \int_{0}^{1} u^{2} \; du = \Biggl[\frac{1}{3}u^{3}\Biggr]_{0}^{1} = \frac{1}{3}

.. container:: æd

   Reiknið eftirfarandi heildi með því að notast við innsetningu.

   -  :math:`\displaystyle \int_{1}^{3} 4x\sqrt{x^{2+1}} \; dx`

   -  :math:`\displaystyle \int_{0}^{1} x^{2}e^{x^{3}} \; dx`

   -  :math:`\displaystyle \int_{1}^{2} \frac{2\ln(x)}{x}\; dx`

Æfing 2
~~~~~~~

#. Reiknið undir-, yfir- og millisummur eftirfarandi falla.

      #. :math:`f(x) = 2x` á bilinu :math:`[0,2]` m.t.t. skiptingarinnar
         :math:`S = \left\{0,\frac{1}{2},\frac{3}{2},2\right\}`

      #. :math:`h(x) = \frac{1}{x^{2}}` á bilinu :math:`[0,3]` m.t.t.
         jöfnu skiptingarinnar :math:`I_{3}`.

      #. :math:`g(x) = e^{x}` á bilinu :math:`[0,1]` m.t.t.
         skiptingarinnar
         :math:`S = \left\{0,\frac{1}{2},\frac{5}{6},1\right\}`. Skilið
         svarinu með :math:`3` aukastöfum.

      #. :math:`f(x) = \cos(x)` á bilinu :math:`\left[0,\pi\right]`
         m.t.t. skiptingarinnar
         :math:`S = \left\{0,\frac{\pi}{4},\frac{\pi}{2},\pi\right\}`.
         Skilið svarinu með :math:`3` aukastöfum.

#. Finnið útgildi fallsins :math:`f` á bilinu :math:`[a,b]` og gerið
      formerkjamynd fyrir afleiðuna. Notið svo niðurstöðurnar til þess
      að finna undir- og yfirsummu fallsins :math:`f` m.t.t.
      skiptingarinnar :math:`S`.

      #. :math:`f(x) = \frac{1}{2}x^{3}-x`,
         :math:`[a,b] = \left[-1,2\right]` og
         :math:`S = \left\{-1,0,\frac{3}{2},2\right\}`.

      #. :math:`f(x) =`, :math:`[a,b] =` og :math:`S = \left\{\right\}`.

#. Notist við gröf eftirfarandi falla til þess að reikna heildin.

      #. Eitthvað

#. Reiknið eftirfarandi heildi.

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

         #. :math:`\displaystyle \int_{}^{} \; dx`

#. Gefið er fallið :math:`f(x) = x` á bilinu :math:`[0,1]`. Sýnið að
      :math:`\displaystyle \lim_{n \to \infty} U_{I_{n}} = \lim_{n \to \infty} Y_{I_{n}}`
      og notfærið ykkur svo þessa niðurstöðu til þess að ákvarða
      :math:`\displaystyle \int_{0}^{1} f(x) \; dx`.

#. Gefin eru föll :math:`f` og :math:`g` á bilinu :math:`[-a,a]` með
      :math:`a > 0`. Einnig er vitað að :math:`f` er **oddstætt fall**
      en :math:`g` er **jafnstætt**. Sýnið að þá gildi eftirfarandi
      reglur:

      #. :math:`\displaystyle \int_{-a}^{a} f(x) \; dx = 0`

      #. :math:`\displaystyle \int_{-a}^{a} g(x) \; dx = 2\int_{0}^{a} g(x) \; dx`

#. Skilgreinum fallið :math:`\ln : ]0,\infty[ \to \mathbb{R}` með því
      að setja

      .. math:: \ln(x) = \int_{1}^{x} \frac{1}{t} \; dt

      Notist við skilgreininguna til þess að sýna eftirfarandi:

      #. :math:`\displaystyle \left(\ln(x)\right)' = \frac{1}{x}`

      #. :math:`\displaystyle \ln\left(a^{b}\right) = b\ln(a)`

      #. :math:`\displaystyle \ln\left(ab\right) = \ln(a)+\ln(b)`

      #. :math:`\displaystyle \ln\left(\frac{a}{b}\right) = \ln(a) - \ln(b)`

   #. Sýna að fallið
      :math:`\displaystyle f(x) = \begin{cases} 1 \text{ ef x er óræð tala}\\ 0 \text{ ef x er ræð tala}\end{cases}`
      sé ekki heildanlegt á :math:`[0,1]`. Sýna fyrst að milli sérhverra
      talna sé til ræð og óræð tala.

Svör við æfingu
~~~~~~~~~~~~~~~

#. 

      #. Fastafall og 0. stigs margliða

      #. Veldisfall og 2. stigs margliða

      #. Hlutleysufall og 1. stigs margliða

      #. 1. stigs margliða

      #. Veldisfall :math:`\left(x^{\frac{1}{2}}\right)`

      #. Fastafall og margliða sem hefur ekkert stig

      #. Rætt fall

      #. 3. stigs margliða

#. 

      #. 
      #. 

#. Svari sleppt.
