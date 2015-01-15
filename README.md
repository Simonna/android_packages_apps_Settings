# android_packages_apps_Settings
<?xml version="1.0" encoding="UTF-8"?>
 <!-- Copyright (C) 2013 SlimRoms Project, Modified by Simonna
 
      Licensed under the Apache License, Version 2.0 (the "License");
      you may not use this file except in compliance with the License.
      You may obtain a copy of the License at
 
           http://www.apache.org/licenses/LICENSE-2.0
 
      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
      See the License for the specific language governing permissions and
      limitations under the License.
 -->
 
 <PreferenceScreen
     xmlns:android="http://schemas.android.com/apk/res/android"
     android:title="@string/recents_settings_title">

    <SwitchPreference
            android:key="recents_use_omniswitch"
            android:title="@string/recents_use_omniswitch_title"
            android:summary="@string/recents_use_omniswitch_summary"
            android:persistent="false" />

    <Preference
            android:key="omniswitch_start_settings"
            android:title="@string/omniswitch_start_settings_title"
            android:summary="@string/omniswitch_start_settings_summary"
            android:persistent="false" />
			
    <!-- Recents Searchbar -->
    <com.android.settings.cyanogenmod.SystemSettingSwitchPreference
        android:key="recents_show_hide_search_bar"
        android:title="@string/recents_show_searchbar"
        android:summary="@string/recents_show_searchbar_summary"
        android:defaultValue="false" />
		
	<!-- Clear button on Navigation Bar --->
	<SwitchPreference
        android:key="clear_all_recents_navbar_enabled"
        android:title="@string/clear_all_recents_navbar_enabled_title"
        android:summary="@string/clear_all_recents_navbar_enabled_summary" />

 </PreferenceScreen>
