# Module 16 — Real-World System Design Case Studies

Fourteen architecture walkthroughs emphasize requirements, explicit scale assumptions, APIs, data ownership, failure handling, security, and operational signals. They are design exercises—not claims that these large products have been implemented here. Numbers are order-of-magnitude examples; revise them when interview assumptions change.

## Case studies

1. [Design URL Shortener (TinyURL)](topics/url-shortener.md)
2. [Design Rate Limiter](topics/rate-limiter.md)
3. [Design Notification System](topics/notifications.md)
4. [Design Chat System (WhatsApp/Slack)](topics/chat.md)
5. [Design News Feed (Twitter/Instagram)](topics/news-feed.md)
6. [Design Video Streaming (YouTube/Netflix)](topics/video-streaming.md)
7. [Design File Storage (Google Drive/Dropbox)](topics/file-storage.md)
8. [Design Search Autocomplete](topics/search-autocomplete.md)
9. [Design E-Commerce (Amazon)](topics/e-commerce.md)
10. [Design Ride Sharing (Uber/Ola)](topics/ride-sharing.md)
11. [Design Payment System](topics/payments.md)
12. [Design Distributed Cache](topics/distributed-cache.md)
13. [Design Ticket Booking (BookMyShow)](topics/ticket-booking.md)
14. [Design Collaborative Editor (Google Docs)](topics/collaborative-editor.md)

## Validate documentation

```bash
python3 scripts/check_links.py
```

## How to use these cases

Start from product constraints rather than copying a diagram. Treat storage choices and throughput calculations as hypotheses, state consistency boundaries, and identify what must be measured in a prototype. Every guide has an architecture diagram and explicitly lists likely failure modes and the trade-offs behind its baseline.

## References

- [Google SRE Book: Addressing cascading failures](https://sre.google/sre-book/addressing-cascading-failures/)
- [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- [RFC 9110: HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110)
- [NIST SP 800-63B: Digital Identity Guidelines](https://pages.nist.gov/800-63-4/sp800-63b.html)
