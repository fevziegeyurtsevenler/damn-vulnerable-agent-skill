# Solution — Invisible Unicode instruction (Tags block)

Learning objective: text you cannot see. The visible body is innocent; an invisible Tags-block payload carries an exfil instruction. uncloak decodes it (**UC101**). Defense: strip U+E0000–E007F; treat any extension containing them as malicious.

Run: `uncloak scan scenarios/02-hidden-unicode`
