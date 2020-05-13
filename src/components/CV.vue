<template>
  <main class="resume">
    <div class="grid grid-cols-12 gap-0 min-h-full">
      <div class="left-content">
        <div class="profile">
          <img class="no-print w-1/2 rounded-full mx-auto" src="imgs/avatar2.jpg" alt />
          <div class="text-center mt-4">
            <p class="font-bold text-xl leading-normal">Rafael Turnes Silveira</p>
          </div>
          <hr class="w-1/4 mx-auto m-2 text-nord14" />
          <div class="job-title">IT Solutions Specialist</div>
        </div>
        <div class="personal">
          <div class="item details">
            <div class="title">Details</div>

            <div class="item nationality">
              <div class="subtitle">Nationality</div>
              <div class="content">Luxembourguer, Brazilian</div>
            </div>

            <div class="item nationality">
              <div class="subtitle">Phone</div>
              <div class="content">+55 48 98415-5757</div>
            </div>

            <div class="item email">
              <div class="subtitle">email</div>
              <div class="content">rafael@turnes.com.br</div>
            </div>
          </div>

          <div class="item languages">
            <div class="title">Languages</div>
            <div class="skill">
              <p>
                Portuguese
                <span class="text-xs">- native speaker</span>
              </p>
              <div class="skill-bar">
                <div class="skill-bar-style w-full"></div>
              </div>
            </div>
            <div class="skill">
              <p>
                English
                <span class="text-xs">- B2</span>
              </p>
              <div class="skill-bar">
                <div class="skill-bar-style w-4/6"></div>
              </div>
            </div>
          </div>

          <div class="item links">
            <div class="title">Links</div>
            <ul class="grid-cols-2">
              <li>
                <a href="https://github.com/turnes" target="_blank">
                  <i class="fab fa-github"></i> GitHub
                </a>
              </li>
              <li>
                <a href="https://www.linkedin.com/in/turnesrafael/" target="_blank">
                  <i class="fab fa-linkedin-in"></i> LinkedIn
                </a>
              </li>
              <!-- <li>
                  <a href="http://turnes.dev" target="_blank"
                    ><i class="far fa-newspaper"></i> Blog</a
                  >
                </li>
                <li>
                  <a href="http://turnes.com.br" target="_blank"
                    ><i class="fas fa-portrait"></i> Site</a
                  >
              </li>-->
            </ul>
          </div>

          <div class="item skills">
            <div class="title">Skills</div>
            <div class="skill">
              <p>Linux</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 80%;"></div>
              </div>
            </div>
            <div class="skill">
              <p>AWS</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 60%;"></div>
              </div>
            </div>
            <div class="skill">
              <p>Azure</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 60%;"></div>
              </div>
            </div>
            <div class="skill">
              <p>Python</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 60%;"></div>
              </div>
            </div>
            <div class="skill">
              <p>Docker</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 80%;"></div>
              </div>
            </div>
            <div class="skill">
              <p>Automation</p>
              <div class="skill-bar">
                <div class="skill-bar-style" style="width: 60%;"></div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="right-content">
        <div class="section profile">
          <div class="title">Profile</div>
          <div class="content">
            Experienced System Administrator and Cloud focused looking for new
            ways to architect and deploy things. I don't like to do boring
            stuff repeatedly. In case I need, I'll find a way to automate it.
            I'm a faster learner and I love to learn new things. I do prefer
            to learn in practice, I'm always doing labs or testing frameworks,
            solutions, etc..
            <br />My background is infrastructure and deploy
            things. But I'm making a move to DevOps related. So recently I've
            taken several mini-courses of development and microservices. I've
            learned HTML, CSS, React, VueJS, NodeJS and Python. Now I know how
            to build and consume API's.
          </div>
        </div>
        <div class="section history">
          <div class="title">Employing History</div>
          <div class="content">
            <ul class="history">
              <li class="history-item">
                <div class="history-title">
                  System Administrator - Santa Catarina State University,
                  Brazil
                </div>
                <div class="history-timespan">May 2015 - PRESENT</div>
                <div class="history-description">
                  Mainly managing network, servers and supporting the users at
                  the university. Some key techs: pfSense, iptables, Huawei
                  networks, Linux, Windows Server, XenServer, Docker, Ansible,
                  FreeNAS, Nextcloud, DokuWiki,
                </div>
              </li>
              <li class="history-item">
                <div class="history-title">IT Technician - Federal Institute of Santa Catarina(IFSC)</div>
                <div class="history-timespan">Feb 2015 - May 2017</div>
                <div
                  class="history-description"
                >IT department manager of campus and network administrator.</div>
              </li>
              <li class="history-item">
                <div class="history-title">IT Solutions Specialist - Beck et al.</div>
                <div class="history-timespan">Feb 2010 - Apr 2014</div>
                <div class="history-description">
                  <ul class="list-disc list-inside">
                    <li>
                      Responsible for implementing and administering company's
                      infras hosted at AWS. Infrastructure based on IBM's
                      solutions like IBM Domino, IBM Quickr, IBM Connections
                      and IBM Sametime and Sugar CRM. Mostly servers were
                      GNU/Linux.
                    </li>
                    <li>
                      Part of an intercontinental and virtual team that
                      administrates a environment (about 80.000 users) of IBM
                      Connections for 2 year.
                    </li>
                  </ul>
                </div>
              </li>
              <!-- <li class="history-item">
                  <div class="history-title">
                    Trainee - Intelbras S.A.
                  </div>
                  <div class="history-timespan">
                    Apr 2007 , Apr 2009
                  </div>
                  <div class="history-description">
                    Worked in a laboratory in Research and Development (R&D)
                    that is responsible for ensuring the quality of new
                    development network Office and Home Office) division.
                  </div>
              </li>-->
            </ul>
          </div>
        </div>
        <div class="section education">
          <div class="title">Education</div>
          <ul class="history">
            <li class="history-item">
              <div class="history-title">Specialization, Specialized in Computer Networking, ESAB</div>
              <div class="history-timespan">Feb 2019 - Apr 2020</div>
              <div class="history-description"></div>
            </li>
            <li class="history-item">
              <div class="history-title">
                University degree, Telecommunications Systems Technology,
                Federal Institute of Santa Catarina
              </div>
              <div class="history-timespan">Feb 2008 - Apr 2013</div>
              <div class="history-description"></div>
            </li>
            <li class="history-item">
              <div class="history-title">
                University degree, Telecommunications Systems Technology,
                Federal Institute of Santa Catarina
              </div>
              <div class="history-timespan">Feb 2008 - Apr 2013</div>
              <div class="history-description"></div>
            </li>
          </ul>
        </div>
        <div class="section courses">
          <div class="title">Courses</div>
          <ul class="history">
            <li class="history-item">
              <div class="history-title">Docker: Administation of Containers - 2020 - 4Linux</div>
              <ul>
                <li>Docker</li>
                <li>UCP</li>
                <li>DTR</li>
                <li>Swarm</li>
                <li>Compose</li>
                <li>Jenkins</li>
                <li>Prometheus/Grafana</li>
                <li>Logs</li>
              </ul>
            </li>
            <li class="history-item">
              <div class="history-title">
                AZ-301: Azure Solutions Architect-Design - 2020 - MS Official
                Course
              </div>
              <ul>
                <li>Design</li>
                <li>Infrastructure</li>
                <li>Identity</li>
                <li>Security</li>
                <li>Migration</li>
                <li>Integration</li>
                <li>Data</li>
              </ul>
            </li>
            <li class="history-item">
              <div class="history-title">
                AZ-300: Azure Architect-Technologies- 2020 - MS Official
                Course
              </div>
              <ul>
                <li>Deploy</li>
                <li>Configure</li>
                <li>Network</li>
                <li>Apps</li>
                <li>Azure AD</li>
                <li>Storage</li>
                <li>Security</li>
                <li>Logs</li>
              </ul>

              <div class="history-description"></div>
            </li>
            <li class="history-item">
              <div class="history-title">Python Programming for SysAdmins - 2019 - 4Linux</div>
              <ul>
                <li>Python</li>
                <li>Flask</li>
                <li>API rest</li>
                <li>Gitlab</li>
                <li>Docker</li>
                <li>MongoDB</li>
                <li>Jenkins</li>
                <li>Logs</li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footer">
      <p>Made with TailwindCSS & Nord theme</p>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style src="../css/resume.css" />
