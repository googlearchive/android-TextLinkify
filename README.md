
Android TextLinkify Sample
===================================

This sample illustrates how links can be added to a TextView. This can be done either
automatically by setting the "autoLink" property or explicitly.

Introduction
------------

This sample demonstrates how clickable links can be added to a `TextView` in Android.

This can be done in three ways:

- **Automatically:** Text added to a TextView can automatically be linkified by enabling
autoLinking. In XML, use the `android:autoLink` property, programatically call
[android.widget.TextView#setAutoLinkMask(int)][1] using an option from
[android.text.util.Linkify][2].
- **Parsing a String as HTML:** See [android.text.Html#fromHtml(String)][3].
- **Manually by constructing a [android.text.SpannableString][4]:** Consisting of
[android.text.style.StyleSpan][5] and [android.text.style.URLSpan][6] objects that
are contained within a [android.text.SpannableString][7].

[1]: http://developer.android.com/reference/android/widget/TextView.html#setAutoLinkMask(int)
[2]: http://developer.android.com/reference/android/text/util/Linkify.html
[3]: http://developer.android.com/reference/android/text/Html.html#fromHtml(java.lang.String)
[4]: http://developer.android.com/reference/android/text/SpannableString.html
[5]: http://developer.android.com/reference/android/text/style/StyleSpan.html
[6]: http://developer.android.com/reference/android/text/style/URLSpan.html
[7]: http://developer.android.com/reference/android/text/SpannableString.html

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.0
- Android Support Repository

Screenshots
-------------

<img src="screenshots/main.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-TextLinkify

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
