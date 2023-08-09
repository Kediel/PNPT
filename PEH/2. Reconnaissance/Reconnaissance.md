<https://www.csoonline.com/article/567859/what-is-osint-top-open-source-intelligence-tools.html>

**OSINT definition**
Open source intelligence (OSINT) is the practice of collecting information from published or otherwise publicly available sources. OSINT operations, whether practiced by IT security pros, malicious hackers, or state-sanctioned intelligence operatives, use advanced techniques to search through the vast haystack of visible data to find the needles they’re looking for to achieve their goals—and learn information that many don’t realize is public. Open source in this context doesn’t refer to the open-source software movement, although many OSINT tools are open source; instead, it describes the public nature of the data being analyzed.

OSINT is in many ways the mirror image of operational security (OPSEC), which is the security process by which organizations protect public data about themselves that could, if properly analyzed, reveal damaging truths. IT security departments are increasingly tasked with performing OSINT operations on their own organizations to shore up operational security.

**OSINT history: From spycraft to IT**
During the 1980s, the military and intelligence services began to shift some of their information-gathering activities away from covert activities like trying to read an adversary’s mail or tapping their phones to discover hidden secrets. Instead, effort was put into looking for useful intelligence that was freely available or even officially published.

The world at the time was changing, and even though social media had not yet made the scene, there were plenty of sources like newspapers and publicly available databases that contained interesting and sometimes useful information, especially if someone knew how to connect a lot of dots. The term OSINT was originally coined to refer to this kind of spycraft.

These same techniques can now be applied to cybersecurity. Most organizations have vast, public-facing infrastructures that span many networks, technologies, hosting services and namespaces. Information can be stored on employee desktops, in legacy on-prem servers, with employee-owned BYOD devices, in the cloud, embedded inside devices like webcams, or even hidden in the source code of active apps and programs.

In fact, the IT staff at large companies almost never knows about every asset in their enterprise, public or not. Add in the fact that many organizations also own or control several additional assets indirectly, such as their social media accounts, and there is potentially a lot of information sitting out there that could be dangerous in the wrong hands.

**Why is OSINT important?**
OSINT is crucial in keeping tabs on that information chaos. IT needs to fulfill three important tasks within OSINT, and a wide range of OSINT tools have been developed to help meet those needs. Most tools serve all three functions, though many excel in one particular area.

Discovering public-facing assets
Their most common function is helping IT teams discover public facing assets and mapping what information each possesses that could contribute to a potential attack surface. In general, they don’t try to look for things like program vulnerabilities or perform penetration testing. Their main job is recording what information someone could publicly find on or about company assets without resorting to hacking.

Discover relevant information outside the organization
A secondary function that some OSINT tools perform is looking for relevant information outside of an organization, such as in social media posts or at domains and locations that might be outside of a tightly defined network. Organizations that have made a lot of acquisitions, bringing along the IT assets of the company they are merging with, could find this function very useful. Given the extreme growth and popularity of social media, looking outside the company perimeter for sensitive information is probably helpful for just about any group.

Collate discovered information into actionable form
Finally, some OSINT tools help to collate and group all the discovered information into useful and actionable intelligence. Running an OSINT scan for a large enterprise can yield hundreds of thousands of results, especially if both internal and external assets are included. Piecing all that data together and being able to deal with the most serious problems first can be extremely helpful.

**Top OSINT tools**
Using the right OSINT tool for your organization can improve cybersecurity by helping to discover information about your company, employees, IT assets and other confidential or sensitive data that could be exploited by an attacker. Discovering that information first and then hiding or removing it could reduce everything from phishing to denial-of-service attacks.

Following (in no particular order) are some of the top tools used for OSINT, what areas they specialize in, why they are unique and different from one another, and what specific value they might be able to bring to an organization’s cybersecurity efforts.

Maltego
Mitaka
SpiderFoot
Spyse
BuiltWith
Intelligence X
DarkSearch.io
Grep.app
Recon-ng
theHarvester
Shodan
Metagoofil
Searchcode
SpiderFoot
Babel X

**Maltego**
Maltego specializes in uncovering relationships among people, companies, domains and publicly accessible information on the internet. It’s also known for taking the sometimes enormous amount of discovered information and plotting it all out in easy-to-read charts and graphs. The graphs do a good job of taking raw intelligence and making it actionable, and each graph can have up to 10,000 data points.

The Maltego program works by automating the searching of different public data sources, so users can click on one button and execute multiple queries. A search plan is called a “transform action” by the program, and Maltego comes with quite a few by default that include common sources of public information like DNS records, whois records, search engines and social networks. Because the program is using public interfaces to perform its searching, it’s compatible with almost any source of information that has a public interface, so adding more searches to a transform action or making up a whole new one is easily possible.

Once the information is gathered, Maltego makes connections that can unmask the hidden relationships between names, email addresses, aliases, companies, websites, document owners, affiliations and other information that might prove useful in an investigation, or to look for potential future problems. The program itself runs in Java, so it works with Windows, Mac and Linux platforms.

There is a free version of the program with limited features called Maltego CE. Desktop versions of Maltego XL run $1,999 per instance. Server installations for large-scale commercial use start at $40,000 and come with a complete training program.

**Mitaka**
Available as a Chrome extension and Firefox add-on, Mitaka lets you search over six dozen search engines for IP addresses, domains, URLs, hashes, ASNs, Bitcoin wallet addresses, and various indicators of compromise (IOCs) from your web browser. sharma osint 1Ax Sharma

The extension saves up your time by acting as a shortcut to various online databases that can be queried with a click.

For those who prefer a focused, more limited set, an alternative extension Sputnik is also available.

**Spiderfoot **
Spiderfoot is a free OSINT reconnaissance tool that integrates with multiple data sources to gather and analyze IP addresses, CIDR ranges, domains and subdomains, ASNs, email addresses, phone numbers, names and usernames, BTC addresses, etc. Available on GitHub, Spiderfoot comes with both a command-line interface and an embedded web-server for providing an intuitive web-based GUI.

The application itself comes with over 200 modules making it ideal for red teaming reconnaissance activities, to discover more information about your target or identify what you or your organisation may be inadvertently exposing on the internet.

**Spyse**
Spyse describes itself as the “most complete internet assets registry” geared toward cybersecurity professionals. Relied on by projects like OWASP, IntelligenceX, and the aforementioned Spiderfoot, Spyse collects publicly available data on websites, their owners, associated servers, and IoT devices. This data is then analyzed by the Spyse engine to spot any security risks in and connections between these different entities.

A free plan is available, although for developers planning on building apps using the Sypse API, paid subscriptions may be required.

**BuiltWith**
As the name implies, BuiltWith lets you find what popular websites are built with. Different tech stacks and platforms power different sites. BuiltWith can, for example, detect whether a website is using WordPress, Joomla, or Drupal as its CMS and provide further details.

BuiltWith also generates a neat list of known JavaScript/CSS libraries (e.g., jQuery or Bootstrap) that a website uses. Further, the service provides a list of plugins installed on the websites, frameworks, server information, analytics and tracking information, etc. BuiltWith can be used for reconnaissance purposes.

What’s more? Combine BuiltWith with website security scanners like WPScan that, for example, integrate with WordPress Vulnerability Database API to spot common security vulnerabilities impacting a website.

For those looking to identify mainly the tech stack makeup of a site, Wappalyzer may be better suited as it provides a more focused, concise output. Try both BuiltWith and Wappalyzer for yourself and see which suits your needs better.

**Intelligence X**
Intelligence X is a first-of-its-kind archival service and search engine that preserves not only historic versions of web pages but also entire leaked data sets that are otherwise removed from the web due to the objectionable nature of content or legal reasons. Although that may sound similar to what Internet Archive’s Wayback Machine does, Intelligence X has some stark differences when it comes to the kind of content the service focuses on preserving. When it comes to preserving data sets, no matter how controversial, Intelligence X does not discriminate.

Intelligence X has previously preserved the list of over 49,000 Fortinet VPNs that were found vulnerable to a Path Traversal flaw. Later during the week, plaintext passwords to these VPNs were also exposed on hacker forums which, again, although removed from these forums, were preserved by Intelligence X.

Previously, the service has indexed data collected from email servers of prominent political figures like Hillary Clinton and Donald Trump. Another recent example of the media indexed by on Intelligence X is the footage from the 2021 Capitol Hill riots and the Facebook’s data leak of 533 million profiles. To intel gatherers, political analysts, news reporters, and security researchers, such information can be incredibly valuable in various ways.

**DarkSearch.io**
While frequent visitors to the dark web may already be familiar with where to look for what, for those who may be new, DarkSearch.io can be a good platform for starting with their research activities. Like another dark web search engine Ahmia, DarkSearch is free but comes with a free API for running automated searches. Although both Ahmia and DarkSearch have .onion sites, you don’t need to necessarily go to the .onion versions or use Tor for accessing either of these search engines. Simply accessing darksearch.io from a regular web browser will let you search the dark web.

**Grep.app **
How do you search across half million git repos across the internet? Sure, you could try individual search bars offered by GitHub, GitLab, or BitBucket, but Grep.app does the job super efficiently. In fact, Grep.app was recently used by Twitter users and journalists on multiple occasions to get an idea of approximately how many repositories were using the Codecov Bash Uploader:

**sharma osint 2**
Ax Sharma
Grep.app can also be useful when searching for strings associated with IOCs, vulnerable code, or malware (such as the Octopus Scanner, Gitpaste-12, or malicious GitHub Action cryptomining PRs) lurking in OSS repos.

**Recon-ng**
Developers who work in Python have access to a powerful tool in Recon-ng, which is written in that language. Its interface looks very similar to the popular Metasploit Framework, which should reduce the learning curve for those who have experience with it. It also has an interactive help function, which many Python modules lack, so developers should be able to pick it up quickly.

Recon-ng automates time-consuming OSINT activities, like cutting and pasting. Recon-ng doesn’t claim that all OSINT gathering can be conducted by its tool, but it can be used to automate much of the most popular kinds of harvesting, leaving more time for the things that still must be done manually.

Designed so that even the most junior Python developers can create searches of publicly available data and return good results, it has a very modular framework with a lot of built-in functionality. Common tasks like standardizing output, interacting with databases, making web requests and managing API keys are all part of the interface. Instead of programming Recon-ng to perform searches, developers simply choose which functions they want it to perform and build an automated module in just a few minutes.

Recon-ng is free, open-source software. The available wiki includes comprehensive information for getting started with the tool as well as best practices for using it.

**theHarvester**
One of the simplest tools to use on this list, theHarvester is designed to capture public information that exists outside of an organization’s owned network. It can find incidental things on internal networks as well, but the majority of tools that it uses are outward facing. It would be effective as a reconnaissance step prior to penetration testing or similar exercises.

The sources that theHarvester uses include popular search engines like Bing and Google, as well as lesser known ones like dogpile, DNSdumpster and the Exalead meta data engine. It also uses Netcraft Data Mining and the AlienVault Open Threat Exchange. It can even tap the Shodan search engine to discover open ports on discovered hosts. In general, theHarvester tool gathers emails, names, subdomains, IPs and URLs.

TheHarvester can access most public sources without any special preparations. However, a few of the sources used require an API key. You must also have Python 3.6 or better in your environment.

Anyone can obtain theHarvester on GitHub. It’s recommended that you use a virtualenv to create an isolated Python environment when cloning it from there.

**Shodan**
Shodan is a dedicated search engine used to find intelligence about devices like the billions that make up the internet of things (IoT) that are not often searchable, but happen to be everywhere these days. It can also be used to find things like open ports and vulnerabilities on targeted systems. Some other OSINT tools like theHarvester use it as a data source, though deep interaction with Shodan requires a paid account.

The number of places that Shodan can monitor and search as part of an OSINT effort is impressive. It’s one of the few engines capable of examining operational technology (OT) such as the kind used in industrial control systems at places like power plants and manufacturing facilities. Any OSINT gathering effort in industries that deploy both information technology and OT would miss a huge chunk of that infrastructure without a tool like Shodan.

In addition to IoT devices like cameras, building sensors and security devices, Shodan can also be turned to look at things like databases to see if any information is publicly accessible through paths other than the main interface. It can even work with videogames, discovering things like Minecraft or Counter-Strike: Global Offensive servers hiding on corporate networks where they should not be, and what vulnerabilities they generate.

Anyone can purchase a Freelancer license and use Shodan to scan up to 5,120 IP addresses per month, with a return of up to a million results. That costs $59 per month. Serious users can buy a Corporate license, which provides unlimited results and scanning of up to 300,000 IPs monthly. The Corporate version, which costs $899 per month, includes a vulnerability search filter and premium support.

**Metagoofil**
Another freely available tool on GitHub, Metagoofil is optimized to extract metadata from public documents. Metagoofil can investigate almost any kind of document that it can reach through public channels including .pfd, .doc, .ppt, .xls and many others.

The amount of interesting data that Metagoofil can gather is impressive. Searches return things like the usernames associated with discovered documents, as well as real names if available. It also maps the paths of how to get to those documents, which in turn would provide things like server names, shared resources and directory tree information about the host organization.

Everything that Metagoofil finds would be very useful for a hacker, who could use it to do things like launch brute-force password attacks or even phishing emails. Organizations that want to protect themselves could instead take the same OSINT gathered information and protect or hide it before a malicious actor can take the initiative.

**searchcode**
For those who need to go really deep into the complex matrix of OSINT gathering, searchcode is a highly specialized search engine that looks for useful intelligence inside source code. This powerful engine is surprisingly the work of a single developer.

Because a repository of code needs to be first added to the program before becoming searchable, searchcode straddles the line between an OSINT tool and one designed to find things other than public information. However, it can still be considered an OSINT tool because developers can use it to discover problems associated with having sensitive information accessible inside code on either running apps or those that are still in development. In the latter case, those problems could be fixed prior to deployment into a production environment.

Although anything involving code is going to require more knowledge than, say, a Google search, searchcode does a great job of making its interface as easy to use as possible. Users simply type in their search fields and searchcode returns relevant results with search terms highlighted in the lines of code. Suggested searches include usernames, security flaws like eval $_GET calls, unwanted active functions like re.compile and special characters that can be used to launch code injection attacks.

Most of the time, the results returned by searchcode are self-explanatory. However, it’s possible to click through those results to find deeper information or matching problems if needed.

**Babel X**
Relevant information isn’t always in English. Only about a quarter of internet users speak English as their primary language according to Statista, though various sources say as much as 55% of internet content is in English. The information you need might be in Chinese, Spanish or Tamil.

Babel X from Babel Street is a multilingual search tool for the public internet, including blogs, social media, message boards and news sites. It also searches the dark web, including Onion sites, and some deep web content that Babel X can access through agreements or licensing from the content owners. The product is able to geo-locate the source of information it finds, and it can perform text analysis to identify relevant results. Babel X is currently capable of searching in more than 200 languages.

Use cases where a multilingual search is useful include searching global news for situational awareness—for example, knowing trends in targeting for ransomware attacks. It can also be used to spot a company’s intellectual property for sale on a foreign website, or information that shows a key partner has been compromised. Customers have also used Babel X to find user handles of suspected attackers on non-English message boards.

The main Babel X product is cloud-based and allows customers to customize it by adding their own data sources to search. Babel Box is an on-premises version but lacks some features of Babel X, such as access to deep web data sources. Babel Channels, the lowest cost option, is a curated collection of data sources. A mobile app is available for all the options.

**OSINT Framework**
While these tools offer a wealth of OSINT data, there are many other tools and techniques available that help you fully understand your organization’s public footprint. An excellent resource for discovering more tools is the OSINT Framework, which offers a web-based interface that breaks down different topic areas of interest to OSINT researchers and connects you to the tools that can help you sniff out the info you need.  

The tools that the OSINT Framework will point you to are all free of charge, though some require registration or have more fully featured paid versions available. Some are simply tools that help construct advanced Google searches that can yield a surprising amount of information. The OSINT Framework is maintained by Justin Nordine, and has a project page on GitHub.

**Is OSINT illegal?**
While OSINT techniques are often used by malicious hackers as reconnaissance before they launch an illegal attack, for the most part the tools and techniques themselves are perfectly legal—after all, they’re designed to help you home in on data that’s published or otherwise in the public view. Even government agencies are encouraged to use OSINT techniques to ferret out holes in their own cybersecurity defenses.

Following the trail opened by these OSINT queries can get you into legal grey areas, however. Media Sonar has some good advice on how to stay on the right side of the law here. For instance, it’s not illegal to access public areas of the dark web, and it can be important to do so if you’re trying to determine if your organization’s data has been breached or stolen; but you shouldn’t try to buy collections of stolen data as part of your research, or impersonate a law enforcement officer to shake information out of shady characters.

In general, it’s important to develop a code of conduct in advance to guide your employees’ behavior on these expeditions, and to document everything you do to demonstrate that you’re sticking to those guidelines and haven’t broken any laws.

**Closing down open-source intelligence loopholes**
Not every hack or intrusion involves advanced persistent threats or deep, sophisticated penetrations. Hackers, like everyone else, will take the easiest path to their objectives. There is no need to try to crack tight cybersecurity through many months of effort if the information they want is available through a publicly accessible channel. At the very least, sensitive information can be used as a shortcut to obtaining valid credentials or to help plan an effective intrusion with less effort or risk.

OSINT tools can help organizations get a grip on what information is available about them, their networks, data and users. Finding that information quickly is key since it would allow for its removal before someone can exploit it. These tools can be a strong boost during that most critical race.
