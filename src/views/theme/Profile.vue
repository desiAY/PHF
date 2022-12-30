<template>
  <CRow>
    <CCol>
      <h1>PROFILE PEGAWAI</h1>
      <CCard class="mb-4">
        <CCardHeader>Jabatan Fungsional Pranata Komputer </CCardHeader>
        <CCardBody>
          <CForm>
            <CFormInput
              type="nama"
              id="exampleFormControlInput1"
              label="Nama Pegawai"
              placeholder=""
              text="Must be 8-20 characters long."
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="nip"
              id="exampleFormControlInput1"
              label="NIP"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>

          <CForm class="mt-2 mb-2">
            <label>Jabatan</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Pilih Jabatan',
                { label: 'Pranata Komputer - Ahli Pertama', value: '1' },
                { label: 'Pranata Komputer - Ahli Muda', value: '2' },
              ]"
            >
            </CFormSelect>
          </CForm>
          <CForm>
            <CFormInput
              type="unit kerja"
              id="exampleFormControlInput1"
              label="Unit kerja"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <CFormInput
              type="satuan kerja"
              id="exampleFormControlInput1"
              label="Satuan kerja"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <br />
          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
