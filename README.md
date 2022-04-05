# Lab 8 - Web Development

 In this lab we developed an additional filter which sits behind the main authentication filter.
 
 To be specific, the first filter was to enforce access to pages only to users which exist in the database, however, this filter enforces protection on administrative routes/pages.
 
 In-order to implement this filter, we needed to add roleId to the session, which happens after the user has been successfully authenticated. Following a redirect, the Administrative Filter will enforce that the role matches an Admin, otherwise, it redirects to another page.
