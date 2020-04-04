# LiveProject
-------------------------------
                                              FESTIVAL EVENT REGISTRATION SYSTEM
                                           ----------------------------------------------
                                         --------------------------------------------------
MODULES IN PROJECT:   
 ----------------------------   
VISITOR:
1.VISITOR LOGIN PAGE
2.NEW USER REGISTRATION PAGE
3.UPDATE VISITOR INFORMATION
4.REGISTER FOR EVENTS
5.UNREGISTER FOR EVENTS
6.CHANGE PASSWORD
---------------------
ADMIN:
1.LOGIN
2.ADD EVENTS
3.UPDTE EVENTS
4.DELETE EVENTS
----------------------------------
FLOW OF THE PROJECT:
CLIENT------> SERVER
--->From web.xml control goes to index.jsp
--->All requests from index.jsp matching .htm pattern automatically will be mapped to Dispatcher Servlet
--->Dispatcher Servlet then looks for xml configuration file Festival-Servlet.xml
--->Dispatcher servlet then scans the base package to look for the specific controller.
--->Controller maps the request to appropriate handler which in turn processes the request and returns the instance of ModelAndView to dispatcher servlet.ModelAndView contains the data and the logical view name
--->Logical view names becomes view objects and InternalResourceViewResolver resolves a logical view name.View page is then displayed to the user.  -----> SERVER----->CLIENT.
LIKE THIS PROJECT FLOW WILL BE CONTINUE.
