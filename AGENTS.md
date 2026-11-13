<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Editorial publishing must use the database approval functions; direct publishing is forbidden because two distinct admins must approve.
- Public analytics records only aggregate event data with an anonymous per-session identifier to avoid collecting personal identities.
- Media remains private; admin previews use short-lived signed links because permanent signed URLs eventually break.
- Media uploads enter a private quarantine and become usable only after server-side signature and malware checks.
- AI recommendations are grounded only in the site's published article catalog and returned slugs are allow-listed.
- Keep header navigation in a dedicated desktop grid and a separate mobile menu; stable item dimensions prevent hover from shifting neighbouring links.
- Use a shared accessible popover for secondary header sections, bounded by the available viewport height so mobile links remain scrollable and reachable.
