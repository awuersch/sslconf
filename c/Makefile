# ---------------------------------------------------------------------------
#  Copyright (c) 2017 Tony Wuersch. All rights reserved.
#  Distributed under the ISC license, see terms at the end of the file.
#  %%NAME%% %%VERSION%% - commit %%VCS_COMMIT_ID%%
# ---------------------------------------------------------------------------

all: dump_config

# requires Openssl
dump_config: dump_config.c
	$(CC) -o $@ $< -lcrypto

clean: dump_config
	rm -f $<

# ---------------------------------------------------------------------------
#  Copyright (c) 2017 Tony Wuersch

#  Permission to use, copy, modify, and/or distribute this software for any
#  purpose with or without fee is hereby granted, provided that the above
#  copyright notice and this permission notice appear in all copies.

#  THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
#  WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
#  MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
#  ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
#  WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
#  ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
#  OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
# ---------------------------------------------------------------------------
