---
lang: ro
title: Codul tău de conduită
description: Facilitează comportamente constructive și sănătoase în comunitate prin adoptarea și impunerea unui cod de conduită.
class: coc
toc:
  why-do-i-need-a-code-of-conduct: "De ce am nevoie de un cod de conduită?"
  establishing-a-code-of-conduct: "Stabilirea unui cod de conduită"
  deciding-how-youll-enforce-your-code-of-conduct: "Decizând cum îți vei impune codul de conduită"
  enforcing-your-code-of-conduct: "Impunerea codului tău de conduită"
  your-responsibilities-as-a-maintainer: "Responsabilitățile tale în calitate de întreținător"
order: 8
image: /assets/images/cards/coc.png
related:
  - building
  - leadership
---

## De ce am nevoie de un cod de conduită?

Un cod de conduită este un document care stabilește așteptări de comportament pentru participanții la proiectul tău. Adoptarea, și aplicarea, unui cod de conduită poate contribui la crearea unei atmosfere sociale pozitive pentru comunitatea ta.

Codurile de conduită ajută la protejarea nu doar a participanților tăi, ci și a ta. Dacă întreții un proiect, ai putea constata că atitudinile neproductive de la alți participanți pot să te facă să te simți stors sau nefericit în legătură cu munca ta de-a lungul timpului.

Un cod de conduită te împuternicește să facilitezi comportament sănătos, constructiv în comunitate. A fi proactiv reduce probabilitatea că tu, sau alții, veți deveni obosiți cu proiectul tău, și te ajută să iei măsuri când cineva face ceva cu care nu ești de acord.

## Stabilirea unui cod de conduită

Încearcă să stabilești un cod de conduită cât mai devreme: în mod idea, când creezi prima dată proiectul.

Pe lângă comunicarea așteptărilor tale, un cod de conduită descrie următoarele:

* Unde are efect codul de conduită _(doar la probleme și cereri de pull, sau activități comunitare cum ar fi evenimente?)_
* La cine se aplică codul de conduită _(membrii comunității și întreținători, dar ce se întâmplă cu sponsorii?)_
* Ce se întâmplă dacă cineva încalcă codul de conduită
* Cum poate cineva semnala încălcări

Oricând poți, folosește stadiul cunoscut al tehnicii. [Contributor Covenant](https://contributor-covenant.org/) este un cod de conduită ușor de instalat care este folosit de peste 40.000 de proiecte cu sursă deschisă, inclusiv Kubernetes, Rails, și Swift.

[Codul de conduită Django](https://www.djangoproject.com/conduct/) și [Citizen Code of Conduct](http://citizencodeofconduct.org/) sunt de asemenea două exemple bune de coduri de conduită.

Amplasează un fișier CODE_OF_CONDUCT în directorul rădăcină al proiectului tău, și fă-l vizibil pentru comunitatea ta legând către el din fișierele tale CONTRIBUTING sau README.

## Decizând cum îți vei impune codul de conduită

<aside markdown="1" class="pquote">
  <p>
    Un cod de conduită care nu este (sau nu poate fi) impus este mai rău decât absența unui cod de conduită: el trimite mesajul că valorile din codul de conduită nu sunt de fapt importante sau respectate în comunitatea ta.
  </p>
  <p>
    <em>
      A code of conduct that isn't (or can't be) enforced is worse than no code of conduct at all: it sends the message that the values in the code of conduct aren't actually important or respected in your community.
    </em>
  </p>
  <p markdown="1" class="pquote-credit">
— [Ada Initiative](https://adainitiative.org/2014/02/18/howto-design-a-code-of-conduct-for-your-community/)
  </p>
</aside>

Ar trebui să explici cum codul tău de conduită va fi impus **_înainte_** ca o încălcare să aibă loc. Sunt câteva motive pentru a face astfel:

* El demonstrează că ești serios în legătură cu luarea de măsuri când este necesar.

* Comunitatea ta se va simți asigurată că plângerile sunt de fapt analizate.

* Îți vei asigura comunitatea că procesul de analizare este corect și transparent, dacă vreodată ei se vor găsi investigați pentru o încălcare.

Ar trebui să oferi oamenilor o cale privată (cum ar fi o adresă de email) pentru a raporta o încălcare a codului de conduită și să explici cine primește raportul. Ar putea fi un întreținător, un grup de întreținători, sau un grup de lucru pentru codul de conduită.

Nu uita că cineva ar putea să vrea să raporteze o încălcare despre o persoană care primește aceste rapoarte. În acest caz, dă-le o opțiune să raporteze încălcările altcuiva. De exemplu @ctb și @mr-c [explică despre proiectul lor](https://github.com/dib-lab/khmer/blob/master/CODE_OF_CONDUCT.rst), [khmer](https://github.com/dib-lab/khmer):

> Exemple de comportament abuziv, hărțuitor, sau altfel inacceptabil pot fi raportate scriind email către **khmer-project@idyll.org** care ajung doar la C. Titus Brown și Michael R. Crusoe. Pentru a raporta o problemă care implică pe oricare din aceștia te rugăm să scrii email către **Judi Brown Clarke, Ph.D.** Directorul pentru Diversitate la Centrul BEACON pentru Studiul Evoluției în Acțiune, un Centru NSF pentru Știință și Tehnologie.
> 
> Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by emailing **khmer-project@idyll.org** which only goes to C. Titus Brown and Michael R. Crusoe. To report an issue involving either of them please email **Judi Brown Clarke, Ph.D.** the Diversity Director at the BEACON Center for the Study of Evolution in Action, an NSF Center for Science and Technology.

Pentru inspirație, aruncă o privire la [manualul impunerii](https://www.djangoproject.com/conduct/enforcement-manual/) al Django (deși poate nu vei avea nevoie de ceva atât de cuprinzător, depinzând de dimensiunea proiectului tău).

## Impunerea codului tău de conduită

Uneori, în ciuda celor mai bune eforturi ale tale, cineva va face ceva ce încalcă acest cod. Există câteva căi de abordare a comportamentului negativ sau dăunător când apare.

### Adună informații despre situație

Tratează fiecare voce a unui membru al comunității ca pe a ta. Dacă primești un raport cum că cineva a încălcat codul de conduită, ia-l în serios și investighează problema, chiar dacă nu se potrivește cu experiența ta proprie cu acea persoană. Făcând astfel va semnala comunității că le prețuiești perspectiva și ai încredere în judecata lor.

The community member in question may be a repeat offender who consistently makes others feel uncomfortable, or they may have only said or done something once. Both can be grounds for taking action, depending on context.

Before you respond, give yourself time to understand what happened. Read through the person's past comments and conversations to better understand who they are and why they might have acted in such a way. Try to gather perspectives other than your own about this person and their behavior.

<aside markdown="1" class="pquote">
  Don’t get pulled into an argument. Don’t get sidetracked into dealing with someone else’s behavior before you’ve finished dealing with the matter at hand. Focus on what you need.
  <p markdown="1" class="pquote-credit">
— Stephanie Zvan, ["So You've Got Yourself a Policy. Now What?"](https://the-orbit.net/almostdiamonds/2014/04/10/so-youve-got-yourself-a-policy-now-what/)
  </p>
</aside>

### Ia măsurile corespunzătoare

After gathering and processing sufficient information, you'll need to decide what to do. As you consider your next steps, remember that your goal as a moderator is to foster a safe, respectful, and collaborative environment. Consider not only how to deal with the situation in question, but how your response will affect the rest of your community's behavior and expectations moving forward.

When somebody reports a code of conduct violation, it is your, not their, job to handle it. Sometimes, the reporter is disclosing information at great risk to their career, reputation, or physical safety. Forcing them to confront their harasser could put the reporter in a compromising position. You should handle direct communication with the person in question, unless the reporter explicitly requests otherwise.

There are a few ways you might respond to a code of conduct violation:

* **Give the person in question a public warning** and explain how their behavior negatively impacted others, preferably in the channel where it occurred. Where possible, public communication conveys to the rest of the community that you take the code of conduct seriously. Be kind, but firm in your communication.

* **Privately reach out to the person** in question to explain how their behavior negatively impacted others. You may want to use a private communication channel if the situation involves sensitive personal information. If you communicate with someone privately, it's a good idea to CC those who first reported the situation, so they know you took action. Ask the reporting person for consent before CCing them.

Sometimes, a resolution cannot be reached. The person in question may become aggressive or hostile when confronted or does not change their behavior. In this situation, you may want to consider taking stronger action. For example:

* **Suspend the person** in question from the project, enforced through a temporary ban on participating in any aspect of the project

* **Permanently ban** the person from the project

Banning members should not be taken lightly and represents a permanent and irreconcilable difference of perspectives. You should only take these measures when it is clear that a resolution cannot be reached.

## Responsabilitățile tale în calitate de întreținător

A code of conduct is not a law that is enforced arbitrarily. You are the enforcer of the code of conduct and it's your responsibility to follow the rules that the code of conduct establishes.

As a maintainer you establish the guidelines for your community and enforce those guidelines according to the rules set forth in your code of conduct. This means taking any report of a code of conduct violation seriously. The reporter is owed a thorough and fair review of their complaint. If you determine that the behavior that they reported is not a violation, communicate that clearly to them and explain why you're not going to take action on it. What they do with that is up to them: tolerate the behavior that they had an issue with, or stop participating in the community.

A report of behavior that doesn't _technically_ violate the code of conduct may still indicate that there is a problem in your community, and you should investigate this potential problem and act accordingly. This may include revising your code of conduct to clarify acceptable behavior and/or talking to the person whose behavior was reported and telling them that while they did not violate the code of conduct, they are skirting the edge of what is expected and are making certain participants feel uncomfortable.

In the end, as a maintainer, you set and enforce the standards for acceptable behavior. You have the ability to shape the community values of the project, and participants expect you to enforce those values in a fair and even-handed way.

## Încurajează comportamentul pe care vrei să îl vezi în lume 🌎

When a project seems hostile or unwelcoming, even if it's just one person whose behavior is tolerated by others, you risk losing many more contributors, some of whom you may never even meet. It's not always easy to adopt or enforce a code of conduct, but fostering a welcoming environment will help your community grow.
