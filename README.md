# Technology Preview: IBM Business Process Manager Analytics
Introduction
=============
The key value of IBM Business Process Manager (BPM) is in streamlining custom enterprise business processes to better optimize service and cost.  It does this namely through 1) custom process applications to manage work, and 2) process analytics for workers, managers, and analysts to assist their decision making in the execution and management of work and the design of processes.  This technology demonstration aims to enhance BPM capabilities for (2) process analytics, with modern technologies which can excel in the era of big data and analytics, taking advantage of the full potential of the rich information into business operations afforded by custom process apps executing in BPM.   

The BPM Analytics aims to enhance BPM for two scenarios: 1) BPM Analytics - providing enhanced process analytics features directly within the BPM offering targeting BPM user roles, and 2) 3rd Party Analytics - providing enhanced features to publish process data to external data and analytics solutions provided by IBM, customers, and partners.  

This demonstration enhances the existing BPM Dynamic Event Framework (DEF) solution to publish business events in JSON message format, after a serial of the reformat and aggregation, store the query-optimized documents at the Elasticsearch, then finally the documents can be fed in the dashboard at the Kibana.

Software Prerequisites
=====================
To use the Analytics in your BPM deployment environment, review the product requirements to ensure that its dependencies are at the required level.
* Elasticsearch & Kibana
  * Version 5.1.x 
  * Version 5.4.x
  * Version 5.5.x
  * By default, Elasticsearch and Kibana have no security.  To use this with any real business data, one will need to subscribe to Elastic X-Pack (https://www.elastic.co/downloads/x-pack) to enable security.
* JRE
  * IBM JRE 7 (Java 7) or IBM JRE 8 (Java 8) - EventSummaryAgent and BPMEventEmitter are compatible with the Java 7 and Java 8, but since the BPM v8600 only support Java 8, the Java 8 is recommended

Version(s) Supported
========================
IBM Business Process Manager V8.6.0.0

Download
=====================
### Stable build
Click on the "release" link at the top of this window to find a stable release of the utilities:
*	EventSummayAgent
*	BPMDashboardKibana
### Development build
Click on the "Clone or download" button at the top of this window to download a .zip containing the three standalone utilities.

Usage Instructions
=====================
For information on how to install and enable BPM Analytics, see ‘IBM Business Process Manager Analytics.pdf’ PDF file.

License Information
====================
See the License folder for more information about how this project is licensed.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


