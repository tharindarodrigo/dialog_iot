<img src="./images/iotdev/image0.png" width="258" height="155" />


Introduction
============

> The objective of this portal is to facilitate set of developer tools
> to onboard, test and publish custom devices. The device vendors and
> SDKs developers can directly interact with the system, by onboarding
> their custom devices that provide specific user scenarios. The tenant
> can use this portal to cater the internal device onboarding
> requirements as well as facilitate the business verticals like
> ‘developer engagement’.
>
> Main areas that can be viewed under Developer Panel are;

-   Device Management

<!-- -->

-   Device operations

-   Device SDKs

-   SCE

-   Reports

-   API Management

-   Advance Operations

-   My Profile

<img src="./images/iotdev/image1.png" width="669" height="382" />The following
depicts the flows of Developer Portal;

Developer Home Page
===================

> In order to login into the Developer Portal, select ‘I am a Developer’
> and it will direct to the Developer Portal login.
>
<img src="../images/iotdev/image2.png" width="624" height="458" />

Developer Portal Login
======================

> A user can enter the email and password credentials to log into the
> system.
>
> Incase if the user has forgotten the password, click on ‘Forgot
> Password’ to define a new password.
>
<img src="../images/iotdev/image3.png" width="624" height="370" />

User Registration
=================

> If a user does not have an account, click on ‘Sign Up’ to create a new
> account.
>
> All fields in the sign up page are mandatory. Once a user clicks on
> ‘Create Account’, he/she is required to wait till the Tenant Admin
> approves the created user.
>
<img src="../images/iotdev/image4.png" width="582" height="326" />

**  
**

1.  Device Management
    =================

### Device Dashboard

> A developer is facilitated to view device dashboard view which
> displays one device per dashboard.
>
> Dashboard can be viewed in diverse types if charts by simply selecting
> from the dropdown. A special feature of this dashboard is that is it
> dynamic therefore user can prioritize the dashboard views as he wish.
>
<img src="../images/iotdev/image5.png" width="604" height="425" />
>
> Follow this procedure to create a customized dashboard;

-   Select the map type

-   Insert a Label

-   Select the device

-   Select the event

-   Finally click on ‘Save Widget’

> Based on the device selection, field input entries may differ to
> extract more accurate results.
>
> Further, user is able to share the dashboard as well.

### Device Operations

> The user is able to perform device configurations using this interface
> where custom devices testing can be performed.
>
> Eg – if user create externally controlled robotic arm using R-pi, he
> can do the testing by controlling the arm using this interface.

### Device Creation

-   Device Addition – this is where user can define a new device

<img src="../images/iotdev/image6.png" width="579" height="286" />

-   Update Device Details – this is the edit view of predefined
    device details.

<img src="../images/iotdev/image7.png" width="579" height="287" />

### Scene Creation

> A scene allows the user to configure device actions to occur based on
> a selected instance.
>
> Eg – if user created a home automation hub using Arduino, he can do
> the test automation by interacting newly created hub operation with
> other standard devices already added to his profile.

-   Click on ‘Add Scene’ in order to define a new scene.

<img src="../images/iotdev/image8.png" width="602" height="291" />
>
> Based on the selection of ‘How to occur’ scene creation instances may
> differ. User will be directed to the following screen displaying three
> instances for a user to manage a scene and they are;

1.  Manual scene

2.  Event base scene

3.  Schedule scene

-   **Manual Scene** – allows to execute scene manually by the user

<img src="../images/iotdev/image9.png" width="591" height="281" />

-   **By Time** - Under Schedule scene the device gets triggered based
    on a particular time frame defined

<img src="../images/iotdev/image10.png" width="596" height="299" />

-   **Device Event** – allows defining a device event occurrence.

<img src="../images/iotdev/image11.png" width="608" height="286" />
>
> **Defining Device and Global Actions**
>
> In each case user can define a device or global action.

-   Click on ‘Add Action’

<img src="../images/iotdev/image12.png" width="614" height="261" />

-   If user wants to execute a particular scene, select a scene out of
    the predefined scene and click on ‘Execute’ button.

<img src="../images/iotdev/image13.png" width="617" height="263" />

<span id="_Toc491965482" class="anchor"><span id="_Toc492047762" class="anchor"></span></span>

Device SDK
========================================================================================================

> Device SDK helps a user to easily connect devices to IoT. Therefore
> simply click on Download button to configure the device. The SDK code
> is open source and can be modified as the user requirement.

<img src="../images/iotdev/image14.png" width="600" height="305" />

API’s Management
================

> This screen exposes APIs of different applications where each beholds
> information such as;

-   Username

-   Consumer key

-   Consumer secret

> Moreover, each application consists of its own Access Token and
> Refresh Tokens to be generated when required.
>
> Each application has its own APIs published, therefore user is able to
> view them and subscribe.

<img src="../images/iotdev/image15.png" width="595" height="465" />

Device Onboarding
=================

> A developer is able to onboard devices on his portal itself by
> configuring the device details and adds related Events and Actions.
>
> Events tab permits the user to define a new event.

<img src="../images/iotdev/image16.png" width="603" height="572" />

Action tab permit the user to define a new action.

Based on the defined action, a json code is generated automatically for
developer reference.

<img src="../images/iotdev/image17.png" width="604" height="462" />

Advance Operations
==================

### Brand Type

> This interface allows defining brand and type by simply clicking on
> the Add button. Once a brand/type is created, the request is sent to
> the device admin for approval and then validated at the backend.

<img src="../images/iotdev/image18.png" width="563" height="351" />

-   Click on ‘Add Brand’ button to define a new brand. User should enter
    a brand name and click on ‘Save’ button.

-   Click on ‘Add Type’ button to define a new type. User should select
    a brand name and enter a type name and click on ‘Save’ button.

    1.  ### Device Definition

> Device definition details are captured at this stage. User is able to
> define basic device details, plugin details and parental details.

<img src="../images/iotdev/image19.png" width="562" height="434" />

> Click on ‘Add Definition’ to define a new record. The following will
> be displayed for the user to enter the details.

<img src="../images/iotdev/image20.png" width="584" height="314" />

-   Define the basic details of a particular device under ‘Basic
    Details’ category.

-   If plugin details are to be defined, first tick on the check box
    under ‘Plugin Details’ category and enter the plugin name and browse
    and select a file.

-   If parent details are to be defined, first tick on the check box
    under ‘Parent Details’ category and enter the event topic and tick
    on sequencing check box.

    1.  ### Actions

> This interface is used to define actions for each predefined device
> definition. Click on Add button to create new actions which allows
> defining action parameters and responses.

<img src="../images/iotdev/image21.png" width="574" height="274" />

-   Click on ‘Add Action’ to define a new action for a
    particular device.

-   Select a Device Definition from the drop down list

-   Click on ‘Add Action’ button, then a list of fields will appear
    allowing the user to define an action. Further user is able to
    define action parameters by clicking on ‘Add Action
    Parameter’ button.

    1.  ### Events

> This allows defining device events for predefined device definition.

<img src="../images/iotdev/image22.png" width="551" height="303" />

-   Click on ‘Add Event’ button to define a new event.

-   Select a Device Definition from the drop down list

-   Click on ‘Add Event’ button, then a list of fields will appear
    allowing the user to define an event. Further user is able to define
    event parameters by clicking on ‘Add Event Parameters’ button and
    also add event statuses.

    1.  ### Events Operations

> This shows the event list of each device. User is facilitated to
> define a new event operation by selecting the appropriate device
> definition and adding operations relating to it.

<img src="../images/iotdev/image23.png" width="574" height="343" />

-   Click on ‘Add Event Operation’ button to define a new event
    operation for a predefined device.

Reports
=======

> A developer is facilitated to view device dashboard view which
> displays one device per dashboard.
>
> Dashboard can be viewed in diverse types if charts by simply selecting
> from the dropdown. A special feature of this dashboard is that is it
> dynamic therefore user can prioritize the dashboard views as he wish.

Follow this procedure to create a customized dashboard;

-   Select the map type

-   Insert a Label

-   Select the device

-   Select the event

-   Finally click on ‘Save Widget’

> Based on the device selection, field input entries may differ to
> extract more accurate results.
>
> Further, user can share the dashboard as well.

My Profile
==========

> A registered user of the developer portal is facilitated to update
> his/her profile when required. Editable fields are only First Name and
> Last Name; other fields such as Email, Phone and Created date are not
> permitted to amend.

<img src="../images/iotdev/image24.png" width="581" height="415" />
