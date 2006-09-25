// $Id$

The restricted_text module provides an input filter allowing authors
to restrict some parts of their text to users with certain roles.

Users can insert [restrict:roles=<comma-separated roles>] and [/restrict]
tags into their text, and anything in-between these will only be visible
to users who are a member of a role in the comma-separated list.  Don't
separate with ', ' (ie, a comma and a space), this version isn't robust
enough to handle that.

As a short-cut for the most common case, [restrict] is equivalent
to [restrict:roles=authenticated user].

This module was developed for the MGH Biostatistics Center.
Please send any questions / comments / suggestions to
    remorse@partners.org
or use the projects interface at Drupal.org.
