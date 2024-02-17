attr_reader :label
74
75 attr_reader pronounceable label.
76
77 # Public: Get the Emoji that this reaction's content represents.
78 #
79 #Returns an Emoji.
80 attr_reader :emoji_character
81
82 def initialize(content:, label: nil, pronounceable_label: nil, emoji_character: nil)
@content content 83
84
@label label || @content
85 @pronounceable_label pronounceable_label || @label
86 @emoji_character emoji_character || Emoji.find_by_alias (@content)
87 @platform_enum @pronounceable_label.gsub("", "_").upcase
PROBLEMS
OUTPUT
[09:43:36] Starting 'watch-extension:vscode-api-tests...
[143:36] Finished clean-extension: typescript-language-features' after 248
[:43:36] Starting watch estension: typescrist-language-features...
[09:43:36 Finished "clean-extensinniphe-language-features after 34 m
[00:43:30] Starting watch-extension.php-language-features...
[:43:40] Finished 'clean-extensinn:htal-language-features-server after 4.50 [09:43:40] Starting watch-extens tonttal-language-features-server.
[es:43:43] Finished "clean-client after 7.33 s
[es:43:43]. Starting watch-client...
[09:44:50] [monaco.d.ts] Starting nonaco.d.ts generation
Tes:44:561 Teonaco.d.tsl Finished nonaco.d.ts generation