---
title: "Declaring RFC 1031, RFC 1480, RFC 1956, and RFC 2146 to be Historic"
abbrev: "RFC 1480 to Historic"
category: info

docname: draft-jabley-rfc1480-to-historic-latest
submissiontype: independent  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
v: 3
keyword:
 - US
 - TLD
 - ccTLD
 - DNS
venue:
  github: "ableyjoe/draft-jabley-rfc1480-to-historic"
  latest: "https://ableyjoe.github.io/draft-jabley-rfc1480-to-historic/draft-jabley-rfc1480-to-historic.html"

author:
 -
    fullname: "Joe Abley"
    organization: Cloudflare
    email: "jabley@cloudflare.com"

normative:

informative:
  RFC1480:
  usTLD:
    target: https://www.about.us/policies
    title: usTLD Policies and Governance
    date: 2026-03-19
  GOV:
    target: https://get.gov
    title: get.gov
    date: 2026-03-19
  MIL:
    target: https://public.sites.disa.ecs.mil/ecs/dns/
    title: DISA
    date: 2026-03-19

--- abstract

The IETF published documents to describe policy and operational model
for some top-level domains at a time where these domains were undelegated. Specifically, "The US Domain" (RFC 1480) described the original structure and related policies for the .US top-level domain. However, many of these operational and policy details have
been superseded. This document reclassifies RFC 1480 as Historic as it is no longer a complete reference for operational or policy matters.

Similarly, this document moves RFC 1031, RFC 1956, and RFC 2146, and to Historic as these domains were delegated to various agencies within the US government.

--- middle

# Introduction

{{RFC1480}}, published in June 1993, described the original structure and related policies for the .US top-level
domain, the country-code top-level domain assigned to the United States of America. At that time, the .US domain was undelegated.

While parts of {{RFC1480}} continue to be relevant at the
time of writing, including the geographic namespace structure and the roles of Delegated
Managers, the document as a whole contains many operational and policy details that have
been superseded.

In order to make it clear that {{RFC1480}} now represents a part of the Internet's
historical record and is no longer a complete reference for operational or policy matters,
this document reclassifies {{RFC1480}} as Historic. This change is also meant to explicitly
indicate that the IETF is not involved anymore in these policy matters. Readers should refer
to authoritative sources on the matter (e.g., {{sec-new-policy}}).

The same reasoning applies for "MILNET Name Domain Transition" {{?RFC1031}}, "Registration in the MIL Domain" {{?RFC1956}}
and "U.S. Government Internet Domain Names" {{?RFC2146}} which contains historical information and do not
reflect operational practices.

# Current Responsibility for the .US/.GOV/.MIL Top-Level Domains {#sec-new-policy}

The U.S. Department of Commerce holds responsibility for the .US Top-Level Domain.

At the time of writing, Registry Services, LLC manages the .US top-level domain on behalf of the U.S.
Department of Commerce. Current policies and governance of the .US top-level domain, including
the hierarchical, locality-based namespace described in {{RFC1480}}, can be found at {{usTLD}}.

Refer to {{MIL}} for .mil and {{GOV}} for .gov.

# IANA Considerations

This document has no IANA actions.

# Operational Considerations

Although {{RFC1480}} might be cited in some service contracts, moving {{RFC1480}} to Historic
does not have operational impact as the binding language is what is indicated in the terms of these contracts, not {{RFC1480}}.

The same considerations apply for {{?RFC1031}}, {{?RFC1956}}, and {{?RFC2146}}.

# Security Considerations

This document does not specify any new protocol and protocol extension. It does not introduce new security threats.

--- back

# Acknowledgments
{:numbered="false"}

Thanks to Michael StJohns for sharing historical background.

