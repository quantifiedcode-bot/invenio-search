..
    This file is part of Invenio.
    Copyright (C) 2015 CERN.

    Invenio is free software; you can redistribute it
    and/or modify it under the terms of the GNU General Public License as
    published by the Free Software Foundation; either version 2 of the
    License, or (at your option) any later version.

    Invenio is distributed in the hope that it will be
    useful, but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with Invenio; if not, write to the
    Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston,
    MA 02111-1307, USA.

    In applying this license, CERN does not
    waive the privileges and immunities granted to it by virtue of its status
    as an Intergovernmental Organization or submit itself to any jurisdiction.

Changes
=======

Version 0.1.3 (released 2015-09-04)

- Fixes potential XSS issues by changing search flash messages
  template so that they are not displayed as safe HTML by default.

- Adds missing `invenio_access` dependency and amends past upgrade
  recipes following its separation into standalone package.

- Displaying HTML safe flash messages can be done by using one of
  these flash contexts: 'search-results-after(html_safe)', 'websearch-
  after-search-form(html_safe)' instead of the standard ones (which
  are the same without '(html safe)' at the end).

Version 0.1.2 (released 2015-08-28)

- Adds missing invenio-knowledge dependency and updates module
  imports.

Version 0.1.1 (released 2015-08-25)

- Adds missing `invenio_upgrader` dependency following its separation
  into standalone package.

- Fixes import of invenio_upgrader.

Version 0.1.0 (released 2015-08-19)

- Initial public release.
