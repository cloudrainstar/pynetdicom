.. _api_dul_pdu_aassociateac:

A-ASSOCIATE-AC PDU
==================

.. currentmodule:: pynetdicom.pdu

An A-ASSOCIATE-AC PDU is made of a sequence of mandatory fields followed by a
variable length field that must contain one Application Context item, one or
more Presentation Context items and one User Information item. Sub-items shall
exist for the Presentation Context and User Information items.

PDU
---

.. autosummary::
   :toctree: generated/

   A_ASSOCIATE_AC

Variable Items
--------------
.. currentmodule:: pynetdicom.pdu_items

.. autosummary::
   :toctree: generated/

   ApplicationContextItem
   PresentationContextItemAC
   UserInformationItem

Presentation Context Sub-items
------------------------------

.. autosummary::
   :toctree: generated/

   AbstractSyntaxSubItem
   TransferSyntaxSubItem

User Information Sub-items
--------------------------

.. autosummary::
   :toctree: generated/

   MaximumLengthSubItem
   ImplementationClassUIDSubItem
   ImplementationVersionNameSubItem
   SCP_SCU_RoleSelectionSubItem
   AsynchronousOperationsWindowSubItem
   UserIdentitySubItemAC
   SOPClassExtendedNegotiationSubItem
   SOPClassCommonExtendedNegotiationSubItem
