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

- Keep the reference reward page at the index route, with presentation tokens in the global stylesheet and shared accessible controls; this keeps the replica consistent and keyboard-accessible.
- Claim buttons link straight to the supplied reward destination, opening in a new tab with rel="noopener noreferrer sponsored"; never fabricate live rewards or collect personal details.
- Prebundle React and the reward page's UI dependencies together in Vite; this prevents first-use optimization from leaving open previews with mismatched React instances.
