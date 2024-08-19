Stofnföll og heildisreglur
--------------------------


.. container:: skilgr

   Gerum ráð fyrir því að :math:`f` sé fall skilgreint á
   :math:`I \subseteq \mathbb{R}`. Ef til er fall :math:`F` sem er
   diffranlegt fyrir öll :math:`x \in I` þannig að :math:`F'(x) = f(x)`
   þá segjum við að :math:`F` sé **stofnfall** fyrir :math:`f` á
   :math:`I`.

.. container:: ath

   Þegar nöfn falla eru gefin með litlum bókstaf, t.d. :math:`f, g, h`
   o.s.frv. þá ef hefð fyrir því að notast við sambærilega stóra stafi
   fyrir nöfn stofnfalla þeirra, t.d. :math:`F, G, H` o.s.frv. Þetta er
   þó ekki nauðsynlegt og notast má við hvern bókstaf eða nafn á
   stofnfallinu sem hentar hverju sinni.

.. container:: ath

   Mikilvægt er að þekkja afleiður algengustu fallanna þegar verið er að
   heilda, en töflu yfir þær má finna í viðauka þessa heftis.

.. container:: regla

   Helstu Diffrunarreglur - Upprifjun Gerum ráð fyrir því að :math:`f`
   og :math:`g` séu diffranleg föll og að :math:`a` sé fasti. Þá gildir:

   -  :math:`\left(f(x)+g(x)\right)' = f'(x)+g'(x)`

   -  :math:`\left(af(x)\right)' = a\left(f(x)\right)'`

   -  :math:`\left(f(x)g(x)\right)' = f'(x)g(x)+f(x)g'(x)`
      (Margföldunarreglan, Leibnitz reglan)

   -  :math:`\left(\dfrac{f(x)}{g(x)}\right)' = \dfrac{f'(x)g(x)-f(x)g'(x)}{g(x)^{2}}`
      (Hlutfallsreglan)

   -  :math:`\left(f(g(x))\right)' = f'(g(x))g'(x)` (Keðjureglan)

.. container:: ath

   Fyrsta reglan hér að ofan felur í sér að sérhvert fall megi diffra
   lið fyrir lið, jafnvel þótt það samanstandi af fleiri en tveimur
   liðum.

.. container:: æd

   Diffrið eftirfarandi föll.

   -  :math:`F(x) = 3x^4-5x^2+2x-1`

   -  :math:`G(x) = 2x^{2}\cos\left(4x-1\right)`

   -  :math:`H(x) = \ln\left(3x^{2}+2\right)`

.. container:: skilgr

   Gerum ráð fyrir að :math:`I \subseteq \mathbb{R}`. Við segjum að
   mengið :math:`I` sé **bil** í :math:`\mathbb{R}` ef fyrir öll
   :math:`a,b` í :math:`I` með :math:`a < b` gildir að ef
   :math:`a < x < b` þá er :math:`x \in I`.

.. container:: ath

   Óformlega má segja að mengi :math:`I \subseteq \mathbb{R}` nefnist
   bil ef það inniheldur engin ”göt”.

.. container:: ath

   Hægt er að sanna að öll bil í :math:`\mathbb{R}` eru af einhverri af
   eftirfarandi gerðum:

   -  Takmörkuðu bilin í :math:`\mathbb{R}`, þ.e. mengi af gerðinni
      :math:`]a,b[`, :math:`]a,b]`, :math:`[a,b[` og :math:`[a,b]` þar
      sem :math:`a` og :math:`b` eru rauntölur og :math:`a < b`.

   -  Hálflínurnar í :math:`\mathbb{R}`, þ.e. mengi af gerðinni
      :math:`]-\infty,a[`, :math:`]-\infty,a]`, :math:`]a,\infty[` og
      :math:`[a,\infty[` þar sem :math:`a` er rauntala.

   -  Mengin :math:`\mathbb{R}` og :math:`\varnothing`.

.. container:: ath

   Í þessu hefti munum við alltaf gera ráð fyrir því að umrædd bil séu
   **ekki** :math:`\varnothing` nema annað sé sérstaklega tekið fram.

.. container:: æd

   Rifjið upp bilritháttinn sem notast var við hér að ofan og skrifið
   sérhverja bilgerð (að :math:`\mathbb{R}` og :math:`\varnothing`
   undanskildum) með mengjarithætti.

.. container:: regla

   Ef :math:`f` er fall skilgreint á bili :math:`I \subseteq \mathbb{R}`
   og :math:`F` og :math:`G` eru tvö stofnföll fyrir :math:`f` á
   :math:`I` þá er til tala :math:`k \in \mathbb{R}` þannig að
   :math:`F(x) = G(x) + k` fyrir öll :math:`x \in I`.

.. container:: sonnun

   Þar sem :math:`F` og :math:`G` eru bæði stofnföll fyrir :math:`f` þá
   fæst

   .. math:: \left(F(x)-G(x)\right)' = F'(x)-G'(x) = f(x)-f(x) = 0

   fyrir öll :math:`x \in I`. Þar með gefur regla úr fyrri áfanga að til
   sé tala :math:`k \in \mathbb{R}` þannig að :math:`F(x) - G(x) = k`
   fyrir öll :math:`x \in I` og því :math:`F(x) = G(x) + k`.

.. container:: ath

   Talan :math:`k` sem kom fram í reglunni hér á undan er yfirleitt
   kölluð **heildisfastinn** sem fæst úr heilduninni. Hann er ætíð stak
   í mengi rauntalna, en við munum ekki tilgreina það sérstaklega héðan
   í frá.

.. container:: æd

   Föllin hér að neðan hafa öll náttúrulega skilgreiningarmengið
   :math:`\mathbb{R}`. Finnið öll stofnföll þeirra á því mengi.

   -  :math:`f(x) = 7+3x^2-5x^5`

   -  :math:`g(x) = 2\cos(3x)`

   -  :math:`h(x) = 3e^{5x}`

.. container:: skilgr

   Við notum táknmálið

   .. math:: \int f(x)\;dx

   til þess að tákna öll stofnföll fallsins :math:`f` og köllum þessa
   stærð **óeiginlega heildi** fallsins :math:`f`.

.. container:: ath

   Óeiginlega heildi fallsins :math:`f` er iðulega bara kallað heildi
   þess, en verknaðurinn að finna það er kallaður að heilda.

.. container:: regla

   Einfaldir eiginleikar heildunar Gerum ráð fyrir því að :math:`f` og
   :math:`g` séu föll á bili :math:`I` og að :math:`a` sé fasti. Þá
   gildir:

   -  :math:`\displaystyle \int f(x)+g(x)\; dx = \int f(x) \; dx + \int g(x) \; dx`.

   -  :math:`\displaystyle \int af(x)\; dx = a\int f(x) \; dx`

.. container:: ath

   Sönnun reglunnar hér að ofan er mjög einföld afleiðing af
   diffrunareglunum í upphafi kaflans og er eftirlátin nemendum.

.. container:: regla

   (Upprifjun á nokkrum velda- og rótarreglum) Eftirfarandi velda- og
   rótarreglur reynast gagnlegar þegar verið er að heilda:

   -  :math:`\displaystyle \sqrt[n]{x} = x^{\tfrac{1}{n}}`

   -  :math:`\displaystyle x^{-n} = \frac{1}{x^{n}}`

   -  :math:`\displaystyle \sqrt[m]{x^{n}} = x^{\tfrac{n}{m}}`

.. container:: æd

   Reiknið eftirfarandi heildi.

   -  :math:`\displaystyle \int 2x^{\tfrac{3}{5}}-5\sqrt[7]{x^{2}} \; dx`

   -  :math:`\displaystyle \int \frac{3}{x^{4}}\; dx`

.. container:: syn

   heildun þar sem skilgreiningarmengið er ekki bil

   Finnum :math:`\displaystyle \int f(x)\; dx` með
   :math:`f(x) = \frac{1}{x}`. Athugum sérstaklega að náttúrulegt
   skilgreiningarmengi :math:`f` er
   :math:`\mathbb{R}\setminus \{0\} = ]-\infty,0[ \cup ]0,\infty[` og
   því er það **ekki** bil heldur sammengi tveggja bila. Við skulum því
   finna stofnfall fyrir :math:`f` á hvoru bili fyrir sig. Byrjum á
   bilinu :math:`]0,\infty[`.

   Nú vitum við að :math:`\left(\ln(x)\right)' = \frac{1}{x}`, og þar
   sem náttúrulegt skilgreiningarmengi :math:`\ln` er :math:`]0,\infty[`
   þá höfum við fundið stofnfall fyrir :math:`f` á því bili.

   Athugum nú að fyrir :math:`x \in ]-\infty,0[` gildir að
   :math:`-x > 0` og því er stærðin :math:`\ln(-x)` skilgreind.
   Keðjureglan gefur nú að
   :math:`\left(\ln(-x)\right)' = \frac{1}{-x}\cdot(-1) = \frac{1}{x}`
   og því er :math:`\ln(-x)` stofnfall fyrir :math:`f` á bilinu
   :math:`]-\infty,0[`.

   Við fáum því að stofnfall fyrir :math:`f` á
   :math:`\mathbb{R}\setminus \{0\}` er gefið með

   .. math:: F(x) = \begin{cases} \ln(x) + k_1 \;\;\;\; \text{ef} \; x > 0\\ \ln(-x) + k_2 \; \text{ef} \; x < 0\end{cases}

   Þar sem :math:`k_1,k_2` eru einhverjir fastar. Þetta má svo umrita

   .. math:: F(x) = \ln|x|+k(x)

   þar sem :math:`k(x) = k_1` ef :math:`x > 0` en :math:`k(x) = k_2` ef
   :math:`x < 0`.

.. container:: ath

   Í flestum kennslubókum stendur einfaldlega að
   :math:`\displaystyle \int \frac{1}{x} \; dx = \ln|x| + k` þar sem
   :math:`k \in \mathbb{R}`. Við munum leyfa okkur að rita þetta með
   þessum hætti þegar verið er að heilda föll sem ekki eru skilgreind á
   bili.

.. container:: æd

   Reiknið heildið :math:`\displaystyle \int \frac{1}{x^{2}} \; dx`.
   Finnið svo stofnfall :math:`F` fyrir fallið
   :math:`f(x) = \frac{1}{x^{2}}` sem uppfyllir skilyrðin
   :math:`F(-1) = 2` og :math:`F(1) = -1` eða tilgreinið af hverju slíkt
   stofnfall er ekki til.

.. container:: regla

   Hlutheildunarregla Gerum ráð fyrir því að fallið :math:`f` sé
   diffranlegt og að :math:`g'` sé afleiða :math:`g`. Þá gildir að

   .. math:: \int f(x)g'(x)\;dx = f(x)g(x) - \int f'(x)g(x)\;dx

.. container:: sonnun

   Margföldunarreglan fyrir diffrun gefur að

   .. math:: \left(f(x)g(x)\right)' = f'(x)g(x) + f(x)g'(x)

   og því fæst að

   .. math:: f(x)g'(x) = \left(f(x)g(x)\right)' - f'(x)g(x)

   Heildum svo og fáum

   .. math:: \int f(x)g'(x)\;dx = f(x)g(x) - \int f'(x)g(x)\;dx

.. container:: ath

   Notkun reglunnar er með þeim hætti að notandinn velur föllin
   :math:`f` og :math:`g'` eftir hentugleika og notast svo við regluna.
   Ef föllin voru vel valin þá ætti heildið sem fæst hægra megin
   jafnaðarmerkisins að vera einfaldara en heildið sem byrjað var með.
   Einnig kemur það oft fyrir að notast þarf við hlutheildunarregluna
   oftar en einu sinni í sama dæminu þar til niðurstaða fæst.

.. container:: syn

   hlutheildun Reiknum eftirfarandi heildi með því að notast við
   hlutheildun.

   -  :math:`\displaystyle \int xe^{x} \; dx`

   -  :math:`\displaystyle \int 2x\cos(x) \; dx`

   -  :math:`\displaystyle \int x\ln(x) \; dx`

   **Lausn:**

   -  Hér veljum við :math:`f(x) = x` og :math:`g'(x) = e^{x}`. Við
      höfum þá að :math:`f'(x) = 1` og :math:`g(x) = e^{x}`. Þar með
      fæst

      .. math::

         \begin{aligned}
         \int xe^{x} \; dx = xe^{x} - \int e^{x} \; dx = xe^{x} - e^{x} + k
         \end{aligned}

   -  Veljum :math:`f(x) = 2x` og :math:`g'(x) = \cos(x)`. Við fáum þá
      að :math:`f'(x) = 2` og :math:`g(x) = \sin(x)`. Því fáum við

      .. math::

         \begin{aligned}
         \int 2x\cos(x) \; dx = 2x\sin(x) - \int 2\sin(x) \; dx = 2x\sin(x) + 2\cos(x) + k
         \end{aligned}

   -  Hér er skynsamlegt að velja :math:`f(x) = \ln(x)` en
      :math:`g'(x) = x`. Við fáum því :math:`f'(x) = \frac{1}{x}` og
      :math:`g(x) = \frac{1}{2}x^{2}` og þar með

      .. math::

         \begin{aligned}
         \int x\ln(x) \; dx = \frac{1}{2}x^{2}\ln(x) - \int \frac{1}{2}x \; dx = \frac{1}{2}x^{2}\ln(x) - \frac{1}{4}x^{2} + k
         \end{aligned}

.. container:: æd

   Reiknið eftirfarandi heildi með því að notast við hlutheildun.

   -  :math:`\displaystyle \int 2x3^{x}\; dx`

   -  :math:`\displaystyle \int x\sin(3x) \; dx`

   -  :math:`\displaystyle \int x^{2}\ln(x)\; dx`

.. container:: regla

   Innsetningarregla

   Ef :math:`F` er stofnfall fyrir fallið :math:`f` og :math:`g'` er
   afleiða fallsins :math:`g` þá gildir að

   .. math:: \int f(g(x))\cdot g'(x)\;dx = F(g(x))+k

.. container:: sonnun

   Við notumst við keðjuregluna og fáum að

   .. math:: \left(F(g(x))\right)' = F'(g(x))\cdot g'(x) = f(g(x))\cdot g'(x)

   Heildun gefur því

   .. math:: \int f(g(x))\cdot g'(x) \;dx = \int \left(F(g(x))\right)' \;dx = F(g(x))+k

.. container:: ath

   Notkun innsetningarreglunnar er með sambærilegum hætti og notkun
   hlutheildunarreglunnar. Við þurfum að velja föllin :math:`f` og
   :math:`g` með skynsamlegum hætti svo hægt sé að beyta reglunni, og í
   kjölfarið finna stofnfallið :math:`F` til þess að komast að
   lokasvarinu.

.. container:: syn

   innsetningu

   Reiknið eftirfarandi heildi með því að notast við innsetningu.

   -  :math:`\displaystyle \int 2x(x^{2}+5)^{8}\; dx`

   -  :math:`\displaystyle \int 3x^{2}\cos\left(x^{3}\right)\; dx`

   -  :math:`\displaystyle \int 5xe^{x^{2}}\; dx`

   **Lausn:**

   -  Ef við veljum :math:`f(x) = x^{8}` og :math:`g(x) = x^{2}+5` þá
      höfum við að :math:`g'(x) = 2x` og því
      :math:`f(g(x))g'(x) = 2x(x^{2}+5)^{8}`. Þar sem
      :math:`F(x) = \frac{1}{9}x^{9}` er stofnfall fyrir :math:`f` þá
      fæst:

      .. math:: \int 2x(x^{2}+5)^{8}\; dx = \frac{1}{9}(x^{2}+5)^{9} + k

   -  Hér getum við valið :math:`f(x) = \cos(x)` og
      :math:`g(x) = x^{3}`. Þá er :math:`g'(x) = 3x^{2}` og því
      :math:`f(g(x))g'(x) = 3x^{2}\cos\left(x^{3}\right)`. Höfum nú
      :math:`F(x) = \sin(x)` og fáum því:

      .. math:: \int 3x^{2}\cos\left(x^{3}\right)\; dx = \sin\left(x^{3}\right) + k

   -  Í fljóti bragði virðist sem við getum ekki notast við
      innsetningarregluna hér, en við þurfum aðeins að byrja á smá
      umritun. Höfum að
      :math:`\displaystyle \int 5xe^{x^{2}}\; dx = \frac{5}{2}\int 2xe^{x^{2}}\; dx`.
      Finnum nú heildið hægra megin jafnaðarmerkisins með því að notast
      við innsetningu. Við veljum :math:`f(x) = e^{x}` og
      :math:`g(x) = x^{2}`. Þá er :math:`g'(x) = 2x` og því fæst
      :math:`f(g(x))g'(x) = 2xe^{x^{2}}`. Við höfum nú
      :math:`F(x) = e^{x}` og fáum því:

      .. math:: \int 5xe^{x^{2}}\; dx = \frac{5}{2}\int 2xe^{x^{2}} \; dx = \frac{5}{2}e^{x^{2}} + k

.. container:: ath

   Í síðasta lið dæmisins hér á undan gæti einhverjum þótt eðlilegra að
   skila svarinu
   :math:`\displaystyle \frac{5}{2}e^{x^{2}}+\frac{5}{2}k`, en þar sem
   fastinn :math:`k` getur verið hvaða rauntala sem er þá gildir slíkt
   hið sama um stærðina :math:`\frac{5}{2}k`. Því má allt eins sleppa
   því að margfalda :math:`\frac{5}{2}` með heildisfastanum.

.. container:: æd

   Reiknið eftirfarandi heildi með því að notast við innsetningu.

   -  :math:`\displaystyle \int 10x\left(5x^{2}-3\right)^{7} \; dx`

   -  :math:`\displaystyle \int 4\sin\left(2x\right) \; dx`

   -  :math:`\displaystyle \int \frac{2x}{x^{2}+1} \; dx`

.. container:: regla

   Innsetningarregla - Gagnlegri útgáfa

   Gerum ráð fyrir að :math:`g'` er afleiða fallsins :math:`g` og að
   :math:`f` sé fall. Ef við setjum :math:`u = g(x)` þá fæst að

   .. math:: \int f(g(x))\cdot g'(x) \;dx = \int f(u)\; du

   þar sem :math:`du = g'(x)dx`.

.. container:: ath

   Þegar við höfum reiknað upp úr heildinu :math:`\int f(u) \; du` þá
   notumst við við jöfnuna :math:`u = g(x)` til þess að fá lokasvarið í
   breytunni :math:`x`.

.. container:: ath

   Í reglunni hér að ofan var notast við bókstafinn :math:`u` í
   innsetningunni, en að sjálfsögðu má notast við hvaða bókstaf sem er.

.. container:: syn

   innsetningu Reiknið eftirfarandi heildi með því að byrja á því að
   notast við innsetningarregluna.

   -  :math:`\displaystyle \int \frac{4}{4x-3}\; dx`

   -  :math:`\displaystyle \int x\sqrt{x-1} \; dx`

   -  :math:`\displaystyle \int x^{3}e^{x^{2}} \; dx`

   **Lausn:**

   -  Setjum :math:`u = 4x - 3`. Við höfum þá að :math:`du = 4x\;dx` og
      við fáum því

      .. math:: \int \frac{4}{4x-3} \; dx = \frac{1}{u} \; du = \ln|u| + k = \ln|4x-3|+k

   -  Hér veljum við :math:`u = x - 1`. Þá fæst :math:`du = dx` en auk
      þess höfum við :math:`x = u + 1`. Við fáum því

      .. math::

         \begin{aligned}
         &\int x\sqrt{x-1} \; dx = \int (u+1)\sqrt{u} \; du = \int u^{\tfrac{3}{2}} + u^{\tfrac{1}{2}} \; du\\ = &\frac{2}{5}u^{\tfrac{5}{2}}+\frac{2}{3}u^{\tfrac{3}{2}} + k = \frac{2}{5}\left(x-1\right)^{\tfrac{5}{2}}+\frac{2}{3}\left(x-1\right)^{\tfrac{3}{2}} + k
         \end{aligned}

   -  Við setjum :math:`u = x^{2}`, fáum þá að :math:`du = 2x \; dx` og
      þar með :math:`\frac{1}{2}du = x\; dx`. Við fáum því

      .. math:: \int x^{3}e^{x^{2}} \; dx = \frac{1}{2}\int u e^{u} \; du

      Við leysum nú þetta heildi með því að notast við hlutheildun, fáum

      .. math:: \frac{1}{2}\int u e^{u} \; du =  \frac{1}{2}\left(ue^{u} - \int e^{u} \; du\right) = \frac{1}{2}ue^{u}-\frac{1}{2}e^{u} + k

      og þar með

      .. math:: \int x^{3}e^{x^{2}} \; dx = \frac{1}{2}x^{2}e^{x^{2}}-\frac{1}{2}e^{x^{2}} + k

.. container:: æd

   Reiknið eftirfarandi heildi með því að notast við
   innsetningarregluna.

   -  :math:`\displaystyle \int \frac{3}{2-5x} \; dx`

   -  :math:`\displaystyle \int 2x\sqrt{x+2}\; dx`

   -  :math:`\displaystyle \int x^{3}\cos\left(2x^{2}\right)\; dx`

.. container:: regla

   (Upprifjun á hornafallareglum) Um hornaföllin :math:`\cos` og
   :math:`\sin` gilda eftirfarandi reglur:

   -  :math:`\displaystyle \cos^{2}(x)+\sin^{2}(x) = 1`

   -  :math:`\displaystyle \cos(2x) = \cos^{2}(x) - \sin^{2}(x)`

   -  :math:`\displaystyle \sin(2x) = 2\sin(x)\cos(x)`

.. container:: ath

   Hornafallareglurnar hér að ofan geta oft reynst gagnlegar við
   heildun.

.. container:: syn

   umritun með hornafallareglum Reiknið eftirfarandi heildi.

   -  :math:`\displaystyle \int \cos^{2}(x) \; dx`

   -  :math:`\displaystyle \int 4\sin(2x)\cos(2x) \; dx`

   -  :math:`\displaystyle \int \cos^{3}(x) \; dx`

   **Lausn:**

   -  Við höum að

      .. math:: \cos(2x) = \cos^{2}(x)-\sin^{2}(x) = \cos^{2}(x) - (1-\cos^{2}(x)) = 2\cos^{2}(x)-1

      og þar með

      .. math:: \cos^{2}(x) = \frac{1}{2}\cos(2x)+\frac{1}{2}

      Við fáum því

      .. math:: \int \cos^{2}(x) \; dx = \int \frac{1}{2}\cos(2x)+\frac{1}{2} \; dx = \frac{1}{4}\sin(2x)+\frac{1}{2}x + k

   -  Setjum :math:`u = 2x`. Þá er :math:`du = 2x \; dx` og við fáum því

      .. math::

         \begin{aligned}
         &\int 4\sin(2x)\cos(2x) \; dx = \int 2\sin(u)\cos(u) \; du \\= &\int \sin(2u) \; du = -\frac{1}{2}\cos(2u) + k = -\frac{1}{4}\cos(2u) + k
         \end{aligned}

   -  Athugum að við höfum

      .. math:: \cos^{3}(x) = \cos(x)\cos^{2}(x) = \cos(x)\left(1-\sin^{2}(x)\right)

      Við setjum því :math:`u = \sin(x)` svo :math:`du = \cos(x) \; dx`
      og því fæst

      .. math::

         \begin{aligned}
         &\int \cos^{3}(x) \; dx = \int \cos(x)\left(1-\sin^{2}(x)\right) \; dx = \int 1 - u^{2} \; du \\= \; &u - \frac{1}{3}u^{3} + k = \sin(x) - \frac{1}{3}\sin^{3}(x) + k
         \end{aligned}

.. container:: syn

   tvö áhugaverð heildi Reiknið eftirfarandi heildi.

   -  :math:`\displaystyle \int \ln(x) \; dx`

   -  :math:`\displaystyle \int e^{x}\sin(x) \; dx`

   **Lausn:** Í báðum þessum dæmum notumst við við sniðug ”trikk” sem
   vert er að muna!

   -  Við umritum :math:`\ln(x) = 1\cdot\ln(x)` og notumst svo við
      hlutheildun. Veljum :math:`f(x) = \ln(x)` og :math:`g'(x) = 1`,
      höfum því :math:`f'(x) = \frac{1}{x}` og :math:`g(x) = x`. Fáum
      því:

      .. math:: \int \ln(x) \; dx = x\ln(x) - \int 1 \; dx = x\ln(x) - x + k

   -  Hér ætlum við að notast við hlutheildun, veljum
      :math:`f(x) = \sin(x)` og :math:`g'(x) = e^{x}`. Höfum því
      :math:`f'(x) = \cos(x)` og :math:`g(x) = e^{x}`. Fáum því:

      .. math:: \int e^{x}\sin(x) \; dx = e^{x}\sin(x) - \int e^{x}\cos(x) \; dx

      Reiknum nú síðara heildið einnig með hlutheildun, veljum
      :math:`f(x) = \cos(x)` og :math:`g'(x) = e^{x}`. Fáum því
      :math:`f'(x) = -\sin(x)` og :math:`g(x) = e^{x}` og þar með

      .. math:: \int e^{x}\cos(x) \; dx = e^{x}\cos(x) + \int e^{x}\sin(x) \; dx

      Ef við tökum saman útreikninga okkar þá höfum við þar með fengið

      .. math::

         \begin{aligned}
         \int e^{x}\sin(x) \; dx &= e^{x}\sin(x) - \left(e^{x}\cos(x) + \int e^{x}\sin(x) \; dx\right)\\ &= e^{x}\sin(x)-e^{x}\cos(x)-\int e^{x}\sin(x) \; dx
         \end{aligned}

      Við sjáum nú að upprunalega heildið okkar kemur fyrir beggja vegna
      jafnaðarmerkisins. Við getum því litið á það sem óþekkta stærð og
      einangrað. Fáum:

      .. math:: \int e^{x}\sin(x) \; dx = \frac{e^{x}\sin(x)-e^{x}\cos(x)}{2} + k

Æfing 1
~~~~~~~

#. Reiknið eftirfarandi heildi.

         #. :math:`\displaystyle \int 2x^{2}-x+3 \; dx`

         #. :math:`\displaystyle \int -5x^{3}+2x-1 \; dx`

         #. :math:`\displaystyle \int 3x^{2}-\sqrt{x} \; dx`

         #. :math:`\displaystyle \int 2x^{\tfrac{1}{3}}+3x^{\tfrac{1}{2}} \; dx`

         #. :math:`\displaystyle \int 3e^{x}-2^{x} \; dx`

         #. :math:`\displaystyle \int e^{5x}+3^{2x} \; dx`

         #. :math:`\displaystyle \int \sqrt{x}-\frac{1}{\sqrt{x}} \; dx`

         #. :math:`\displaystyle \int e^{-x}+\sqrt[3]{x} \; dx`

         #. :math:`\displaystyle \int \frac{3}{x^{2}+1} \; dx`

         #. :math:`\displaystyle \int \frac{2}{3x} \; dx`

         #. :math:`\displaystyle \int -\frac{\pi}{x-e} \; dx`

         #. :math:`\displaystyle \int 3\cos(3x)-4\sin(2x) \; dx`

         #. :math:`\displaystyle \int \frac{1}{\pi}\cos(2\pi x)+\frac{2}{\pi}\sin(\pi x) \; dx`

         #. :math:`\displaystyle \int \frac{3}{\sqrt{1-x^{2}}} \; dx`

         #. :math:`\displaystyle \int 1 + \tan^{2}(x) \; dx`

         #. :math:`\displaystyle \int \frac{1}{\cos^{2}(x)} \; dx`

#. Reiknið heildið :math:`\displaystyle \int f(x) \; dx` og finnið
   síðan stofnfall :math:`F` fyrir :math:`f` sem uppfyllir skilyrðin
   :math:`F(-1) = 1` og :math:`F(1) = 2` eða útskýrið af hverju slíkt
   stofnfall er ekki til.

         #. :math:`f(x) = \dfrac{1}{x}`

         #. :math:`f(x) = 3x^{2}`

         #. :math:`f(x) = \dfrac{2}{x^{3}}`

         #. :math:`f(x) = \cos(\pi x)`

#. Notist við hlutheildun til þess að reikna eftirfarandi heildi.

         #. :math:`\displaystyle \int xe^{3x} \; dx`

         #. :math:`\displaystyle \int 2x\cos(3x) \; dx`

         #. :math:`\displaystyle \int x\ln(x) \; dx`

         #. :math:`\displaystyle \int xe^{-x} \; dx`

         #. :math:`\displaystyle \int 3x\sin(x) \; dx`

         #. :math:`\displaystyle \int x^{3}\ln(x) \; dx`

         #. :math:`\displaystyle \int x^{2}\cos(x)\; dx`

         #. :math:`\displaystyle \int x^{2}2^{-x}\; dx`

         #. :math:`\displaystyle \int x\left(\ln(x)\right)^{2} \; dx`

         #. :math:`\displaystyle \int \sqrt{x}\ln(x) \; dx`

         #. :math:`\displaystyle \int x\log_{10}(x) \; dx`

         #. :math:`\displaystyle \int \frac{\ln(x)}{x^{2}}\; dx`

#. Notist við innsetningu til þess að reikna eftirfarandi heildi.

         #. :math:`\displaystyle \int 2x\left(x^{2}+1\right)^{4} \; dx`

         #. :math:`\displaystyle \int 3x^{2}\sqrt{x^{3}+1} \; dx`

         #. :math:`\displaystyle \int 4x\cos\left(x^{2}\right) \; dx`

         #. :math:`\displaystyle \int 5x^{2}e^{x^{3}} \; dx`

         #. :math:`\displaystyle \int x^{3}\left(x^{4}-2\right)^{9}\; dx`

         #. :math:`\displaystyle \int \frac{1}{\pi}\sin\left(\pi x\right)\; dx`

         #. :math:`\displaystyle \int 3x3^{x^{2}} \; dx`

         #. :math:`\displaystyle \int 3x\sqrt{8-x^{2}} \; dx`

         #. :math:`\displaystyle \int \frac{3^{\ln(x)}}{x} \; dx`

         #. :math:`\displaystyle \int x^{5}\sqrt{x^{2}+1} \; dx`

         #. :math:`\displaystyle \int (x^2-1)(x^3-3x+2)^{3} \; dx`

         #. :math:`\displaystyle \int \frac{\ln(\ln(x))}{x} \; dx`

#. Reiknið eftirfarandi heildi.

         #. :math:`\displaystyle \int \sin^{2}(x) \; dx`

         #. :math:`\displaystyle \int x\cos(2\pi x)\sin(2\pi x) \; dx`

         #. :math:`\displaystyle \int \cos^{2}(\pi x) \; dx`

         #. :math:`\displaystyle \int \cos^{5}(x) \; dx`

         #. :math:`\displaystyle \int 2^{x}\cos(x) \; dx`

         #. :math:`\displaystyle \int \sqrt{x}\sin\left(\sqrt{x}\right) \; dx`

         #. :math:`\displaystyle \int \cos(\ln(x)) \; dx`

         #. :math:`\displaystyle \int \frac{5^{\ln(x)}}{x^{2}}\; dx`

         #. :math:`\displaystyle \int \arctan(x) \; dx`

         #. :math:`\displaystyle \int \frac{1}{e^{x}+e^{-x}} \; dx`



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
