# React Router Catch-All Route Issue

This repository demonstrates a common issue with React Router's catch-all route (`/*`).  The problem arises when the catch-all route interferes with other, more specific routes, even if those routes should match first. 

The solution involves carefully ordering routes and making sure more specific routes appear before the catch-all route.